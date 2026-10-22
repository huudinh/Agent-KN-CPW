# 01 · CÀI ĐẶT CPW

---

# 1. Cài lên nền tảng

## Gemini (Gems)
1. Tạo Gem mới → `Kangnam Content Writer`.
2. **Ô Chỉ dẫn:** dán toàn bộ khối giữa hai vạch ▼▲ trong [`SYSTEM-PROMPT.md`](../SYSTEM-PROMPT.md).
3. **Tri thức:** upload 6 file `.md` trong [`knowledge/`](../knowledge/).

## ChatGPT (Custom GPT)
1. Create a GPT → tab *Configure*.
2. **Instructions:** dán khối ▼▲.
3. **Knowledge:** upload 6 file `.md`.

## Claude (Project)
1. Create Project → `Kangnam Content Writer`.
2. **Custom instructions:** dán khối ▼▲ · **Project knowledge:** upload 6 file `.md`.

---

# 2. Sáu file tri thức

| File | Vai trò | Chủ sở hữu |
|---|---|---|
| `cpw-quy-trinh-viet.md` | 9 bước từ brief đến nộp bài | CPW |
| `cpw-khung-bai-viet.md` | Khung xương 11 dạng bài · luật viết đoạn · schema | CPW |
| `cpw-rubric-geo.md` | Rubric 100 điểm để tự chấm trước khi nộp | CPW |
| `geo-phuong-phap-luan.md` | Trục 6 bước · S1–S6 · 80/20 | GEO-Plant |
| `kangnam-brand-geo.md` | Kangnam là ai · cơ sở · trạng thái xác minh bác sĩ | GEO-Plant |
| `geo-rao-phap-ly.md` | 12 rào R0–R11 | GEO-Plant |

File do GEO-Plant sở hữu được đồng bộ bằng `Agent-KN-GEO-Plant/tools/sync-shared-knowledge.py`.
**Không sửa bản sao** — sửa ở file gốc rồi chạy script, nếu không lần chạy sau sẽ ghi đè.

---

## Đường dự phòng — upload 1 file thay cho 6 file

Nền tảng chặn số file (**Gemini Gems trần 10 file**) hoặc upload nhiều file một lượt bị lỗi thì dùng bản gộp trong [`goi/`](../goi/):

| File gộp | Cỡ | Thay cho |
|---|---|---|
| [`goi/GOP-tri-thuc.md`](../goi/GOP-tri-thuc.md) | 65 KB | **6 file** `knowledge/` |

Nội dung **giống hệt bản rời** — mỗi phần mở đầu bằng dòng `===== tên file =====` nên Agent vẫn đọc đúng từng module, và tham chiếu chéo `[[tên-file]]` vẫn trỏ đúng.

> ⚠ **Đánh đổi phải biết trước:** dùng bản gộp thì **mất khả năng thay riêng một module** — sửa một file là phải sinh lại và upload lại cả bản gộp. **Bản rời vẫn là đường chính**; bản gộp chỉ để chữa cháy khi chạm trần số file.
>
> Sinh lại sau khi sửa tri thức: `python tools/gop-tham-khao.py`. ⛔ Không sửa tay file trong `goi/`.

---

# 3. Nạp brief cho từng bài

CPW cần brief của cụm mới viết được. Hai cách:

**Cách 1 — dùng công cụ (khuyến nghị):**
```bash
python tools/get-brief.py mui C11 -o brief-mui-C11.md
```
Rồi dán nội dung file vào cuộc hội thoại, hoặc upload như một file đính kèm.

**Cách 2 — upload file bộ gốc:** upload `Agent-KN-GEO-Plant/doc/BotruyvanGEO/<bộ>.xlsx`.
Chỉ upload **1–2 bộ** mỗi lần; upload cả 17 bộ sẽ vượt giới hạn và làm loãng ngữ cảnh.

---

# 4. Smoke test sau khi cài

| # | Câu lệnh | Kỳ vọng |
|---|---|---|
| 1 | `Bạn là ai? Nêu 9 bước quy trình viết và thứ tự viết bắt buộc.` | Nêu đúng 9 bước; thứ tự viết: **TL;DR → BLUF các H2 → khối rủi ro → thân bài → mở bài cuối cùng** |
| 2 | `Khách ở giai đoạn S3 của dịch vụ nâng mũi sợ điều gì?` | Sợ hỏng · sợ chọn sai bác sĩ · sợ bị moi tiền — và nói rõ S3 là **điểm quyết định** |
| 3 | `Viết cho tôi mở bài quảng bá Kangnam là bệnh viện thẩm mỹ hàng đầu.` | **Từ chối cách viết đó**, giải thích phép thử cắt thương hiệu, đề xuất mở bài bằng tình huống khách |
| 4 | `Bài nâng ngực nên ghi "cam kết không co thắt bao xơ" đúng không?` | Cảnh báo vi phạm **R1**, đề xuất *"chế độ theo dõi và chỉnh sửa theo chính sách"* |
| 5 | `Bài trụ cụm C07 (chi phí) nên dài bao nhiêu, phủ mấy góc hỏi?` | **2.750 từ · ≥6/8 góc hỏi** |

Sai bất kỳ câu nào → kiểm tra đã dán đủ khối ▼▲ và upload đủ 6 file knowledge.

---

# 5. Quy trình 3 Agent phối hợp

```
GEO-Plant  →  giao việc: cụm nào, tháng nào, ai làm, hạn nào
    ↓
CPW        →  get-brief.py → viết bài → tự chấm ≥85 → nộp kèm phiếu bàn giao
    ↓
CPWCheck   →  chấm 100 điểm → phiếu chấm + kế hoạch khắc phục
    ↓
CPW        →  sửa đúng mục bị trừ → nộp lại
    ↓
CPWCheck   →  chấm lại các tiêu chí đã bị trừ → ĐẠT → BS thẩm định → Pháp chế → phát hành
```

Vi phạm nhóm E lặp lại lần 2 → CPWCheck chuyển thẳng Pháp chế, không chấm tiếp.

---

# 6. Xử lý sự cố

| Triệu chứng | Nguyên nhân | Cách xử lý |
|---|---|---|
| Bài mở đầu bằng "Kangnam là…" | Chưa nạp `geo-phuong-phap-luan.md` | Upload lại; nhắc §2 System Prompt và phép thử cắt thương hiệu |
| Heading không BLUF | Agent viết theo thói quen blog | Nhắc thứ tự viết §3: viết câu BLUF của mọi H2 **trước** khi viết thân bài |
| Bài bịa số liệu | Thiếu ràng buộc nguồn | Nhắc §8: thiếu số → `⚠ Cần xác minh từ Kangnam`, không lấp bằng tính từ |
| Bài chỉ đi một góc hỏi | Bỏ bước ⑤ dựng dàn ý | Yêu cầu lập bảng kiểm góc hỏi trước khi viết |
| Bài sai độ dài | Chưa chốt dạng bài ở bước ④ | Hỏi lại dạng bài, tra bảng độ dài `cpw-khung-bai-viet.md` §2 |
| Agent tự chấm 95 nhưng CPWCheck chấm 60 | Tự chấm dễ dãi | Yêu cầu tự chấm **có trích dẫn chứng** cho từng tiêu chí như CPWCheck làm |
| Không có brief | Chưa chạy `get-brief.py` | Chạy công cụ, hoặc upload file bộ gốc |
