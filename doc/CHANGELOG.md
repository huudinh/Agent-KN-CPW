# CHANGELOG — CPW


## Bản gộp dự phòng cho file tri thức — 22/10/2026

Thêm 1 file gộp trong `goi/` và `tools/gop-tham-khao.py` để sinh lại:

- `goi/GOP-tri-thuc.md` — gộp **6 file** `knowledge/` (65 KB)

**Vì sao cần:** Gemini Gems chặn ở **10 file** tri thức, và upload hàng chục file một lượt rất hay lỗi. Gặp trần thì trước giờ không có đường nào ngoài bỏ bớt file — mà bỏ bớt file tri thức là bỏ bớt luật, và luật bị bỏ thường là luật pháp lý vì nó nằm ở file người ta tưởng không quan trọng.

**Không mất nội dung nào.** Mỗi phần trong bản gộp mở đầu bằng dòng `===== tên file =====`, nên Agent vẫn đọc đúng từng module và tham chiếu chéo `[[tên-file]]` vẫn trỏ đúng — chỉ đổi chỗ nằm, không đổi mã. Đã đối chiếu từng byte với bản rời.

**Đánh đổi, đã ghi vào `doc/01-cai-dat.md`:** dùng bản gộp thì **mất khả năng thay riêng một module** — sửa một file là phải sinh lại và upload lại cả bản gộp. **Bản rời vẫn là đường chính**; bản gộp chỉ để chữa cháy khi chạm trần.

⛔ Không sửa tay file trong `goi/`. Sửa ở thư mục nguồn rồi chạy `python tools/gop-tham-khao.py`.

---

## Đồng bộ dữ liệu bác sĩ & cơ sở với site production — 16/10/2026

Đối chiếu trực tiếp `/doi-ngu-bac-si/` · `/chi-nhanh/` · menu chính (16/10/2026). **Chỉ sửa file tri thức brand, không đụng bộ não.**

**Sửa `knowledge/kangnam-brand-geo.md` — bảng cơ sở.** Trang `/chi-nhanh/` hiện công bố **7 cơ sở tại 7 tỉnh thành**: 2 bệnh viện (Hà Nội 190 Trường Chinh — GP **194/BYT-GPHĐ**; Sài Gòn 666 CM Tháng 8 — GP **287/BYT-GPHĐ**) + 5 viện thẩm mỹ (Hải Phòng · Nghệ An · Đà Nẵng · Cần Thơ · Thanh Hóa). File đang ghi *"3 bệnh viện + 7 viện"* (10 cơ sở).

⚠️ **Ba cơ sở trong bảng không có trên `/chi-nhanh/`** — đã gắn cờ, **chưa xoá**: `BVTM Kangnam CS2 – 218 Nguyễn Trãi` · `Viện Trẻ hoá & Điều trị da công nghệ cao – 194 Trường Chinh` · `Chi nhánh Bình Dương`.
Chưa đủ căn cứ nói ba cơ sở này đã đóng (có thể là pháp nhân khác hoặc trang chưa cập nhật). Nhưng GEO/local nói về **địa điểm**, nên nêu sai một cơ sở là chạm rào **R3 (đúng pháp nhân)**.

→ **Luật tạm thời: nội dung local chỉ dùng 7 cơ sở có trên `/chi-nhanh/`.** Ba cơ sở còn lại chỉ dùng sau khi Pháp chế xác nhận còn hoạt động và còn giấy phép.
Chụp lại: `python ../Agent-LDP-Kangnam/tools/fetch-du-lieu.py --chi co_so`

---

## v1.0 — 14/09/2026

Bản đầu tiên của **Kangnam Content Production Writer**, agent thứ 2 trong bộ ba
`GEO-Plant` (lập kế hoạch) → **`CPW` (viết bài)** → `CPWCheck` (chấm điểm).

**Bộ não**
- `SYSTEM-PROMPT.md` — 14 mục. Trọng tâm §2 (phép thử cắt thương hiệu), §3 (quy trình 9 bước + thứ tự viết bắt buộc), §4 (nỗi sợ theo giai đoạn), §11 (tự chấm ≥85 mới được nộp), §12 (4 phần đầu ra).

**Tri thức riêng của CPW**
- `cpw-quy-trinh-viet.md` — 9 bước từ brief đến nộp bài; thứ tự viết: TL;DR → BLUF các H2 → khối rủi ro → thân bài → mở bài cuối cùng.
- `cpw-khung-bai-viet.md` — 4 nhóm sản xuất, **11 dạng bài với độ dài đo từ 1.363 đầu việc thật**, khung xương 7 dạng chính, luật viết đoạn, schema JSON-LD theo dạng.
- `cpw-rubric-geo.md` — **rubric 100 điểm dùng chung với CPWCheck**: A Hành trình 25 · B Cấu trúc AI 25 · C Bằng chứng 15 · D Thực thể & kỹ thuật 15 · E Pháp lý 20 (cổng chặn) · F điểm trừ.

**Tri thức đồng bộ từ GEO-Plant**
`geo-phuong-phap-luan.md` · `kangnam-brand-geo.md` · `geo-rao-phap-ly.md`

**Công cụ**
- `tools/get-brief.py` — trích brief một cụm từ bộ truy vấn: hành vi khách của giai đoạn, góc hỏi, rào pháp lý, từng truy vấn kèm *khối trả lời cần có*. Hỗ trợ `--sets` · `--list` · `--core` · `-o`.

**Dữ liệu nền mới đo được trong bản này**
- **4.311 truy vấn** trên 17 bộ → phân bổ 8 góc hỏi fan-out: Trường hợp áp dụng 24,6% · Hướng dẫn & quy trình 19,1% · Phản đối & rủi ro 15,1% · Định nghĩa 11,1% · Thực thể & kiểm chứng 9,7% · So sánh 8,3% · Chi phí & chỉ số 7,8% · Địa phương 4,1%. **Ba góc đầu chiếm ~59%.**
- **1.363 đầu việc** trong checklist → 4 nhóm sản xuất (A1 381 bài · A2 609 · B 86 · C 264 · D 23) và dải độ dài chuẩn của từng dạng bài.

---

## Việc còn treo

| Hạng mục | Ảnh hưởng |
|---|---|
| Danh sách bác sĩ đã xác minh chuyên khoa (KF-02) | Mọi bài đang để `⚠ Cần xác minh` ở author box → chưa đạt D2 trọn vẹn, và chặn E2 |
| Bảng giá min–max đã được duyệt công khai | Chưa viết được Trang chức năng (bảng giá) — cụm Tầng A của hầu hết các bộ |
| Kho case có văn bản đồng ý minh thị | Chưa dùng được case thật, mất một nguồn bằng chứng mạnh (R5) |
| Số liệu tỷ lệ biến chứng theo từng dịch vụ | Bài biến chứng đang thiếu con số — ảnh hưởng trực tiếp C1 |
| Phạm vi giấy phép chi tiết từng cơ sở | Trang local chưa ghi chính xác "làm được gì / không làm gì" (R3) |
