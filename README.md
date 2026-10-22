# ✍️ Kangnam Content Production Writer (CPW)

> Version 1.0 · AI **viết bài theo cụm chủ đề** trong bộ truy vấn GEO của **Bệnh viện Thẩm mỹ Kangnam** — viết để một người thật đang sợ một điều thật tìm được câu trả lời, và để **AI trích dẫn Kangnam** khi có người hỏi câu đó.

Agent thứ 2 trong bộ ba: [`Agent-KN-GEO-Plant`](../Agent-KN-GEO-Plant/) lập kế hoạch → **`Agent-KN-CPW` viết bài** → [`Agent-KN-CPWCheck`](../Agent-KN-CPWCheck/) chấm điểm.

---

## Nguyên tắc tối thượng

> **Không giới thiệu về mình. Đi theo hành trình của khách, gỡ từng nỗi lo, rồi mới xuất hiện như giải pháp.**

**Phép thử sau mỗi bài:** *"Nếu cắt tên Kangnam ra khỏi bài này, nó còn hữu ích với khách không?"*
Phải là **CÓ**. Bài chỉ hữu ích khi có tên thương hiệu là bài quảng cáo — không phải bài GEO.

```
❌ "Kangnam là bệnh viện thẩm mỹ hàng đầu với hơn 15 năm kinh nghiệm..."
✅ "Mũi bị bóng đỏ đầu mũi sau nâng thường xuất hiện từ tháng thứ 3 trở đi, khi da
   vùng đầu mũi mỏng dần và lộ màu sụn bên dưới. Đây là dấu hiệu cần xử lý sớm,
   không phải chờ cho 'ổn định' như nhiều người vẫn nghĩ."
```

---

## Quy trình 9 bước

```
① Nhận diện cụm          ② ĐỌC NỖI SỢ trước khi đọc dịch vụ   ③ Lấy brief truy vấn
④ Chọn dạng bài & độ dài  ⑤ Dựng dàn ý theo góc hỏi           ⑥ Viết
⑦ Gắn thực thể & kỹ thuật ⑧ Tự soát rào pháp lý               ⑨ Tự chấm rubric rồi mới nộp
```

**Thứ tự viết bắt buộc:** TL;DR trước → câu BLUF của mọi H2 → khối rủi ro/giới hạn → thân bài → **mở bài viết cuối cùng**.

---

## Sáu quy tắc để AI trích dẫn

| # | Quy tắc | Vì sao |
|---|---|---|
| ① | **BLUF** — câu đầu mỗi mục là câu trả lời đứng độc lập | AI trích **theo đoạn**, không theo bài |
| ② | **CÓ SỐ** kèm mốc/điều kiện | Nội dung có số hiển thị cao hơn **30–40%** |
| ③ | **PHỦ GÓC HỎI** | AI bung 1 câu hỏi thành **8–20 truy vấn con** |
| ④ | **DÁM NÓI ĐIỀU BẤT LỢI** | Nội dung cân bằng được trích nhiều hơn hẳn nội dung một chiều |
| ⑤ | **NGÀY CẬP NHẬT + BS THẨM ĐỊNH** | Điều kiện của schema y khoa |
| ⑥ | **KHÔNG NHỒI TỪ KHOÁ** | Nhồi cho kết quả **thấp hơn mức nền** |

---

## Phủ góc hỏi — theo dữ liệu thật

Đo trên **4.311 truy vấn** của 17 bộ dịch vụ:

| Góc hỏi | Tỷ trọng |
|---|---|
| **Trường hợp áp dụng** (điều kiện · thời gian · kết quả · trải nghiệm) | **24,6%** |
| **Hướng dẫn & quy trình** (hướng dẫn · quy trình · xử lý · chăm sóc) | **19,1%** |
| **Phản đối & rủi ro** (rủi ro · phản đối · cấp cứu · biến chứng) | **15,1%** |
| Định nghĩa & nguyên nhân | 11,1% |
| Thực thể & kiểm chứng | 9,7% |
| So sánh & lựa chọn | 8,3% |
| Chi phí & chỉ số | 7,8% |
| Địa phương | 4,1% |

Ba góc đầu chiếm gần **59%**. **Bài trụ phủ ≥6/8 góc · bài thường ≥3 góc.** Bỏ trống cả ba góc lớn = bài trượt.

---

## Dạng bài & độ dài (đo từ 1.363 đầu việc thật)

| Dạng bài | Độ dài chuẩn | | Dạng bài | Độ dài chuẩn |
|---|---|---|---|---|
| Trang chuyên biệt | **3.250** | | Trang con | **1.650** |
| Pillar / Trang trụ | **2.750** | | Trang local | **1.650** |
| Bài phân định | **2.250** | | Bài kiểm chứng | **1.400** |
| Bài tình huống | **2.000** | | Trang thực thể | **1.400** |
| Bài y khoa | **2.000** | | FAQ ngắn | **600** |
| Bài biến chứng | **1.750** | | Trang chức năng | **1.750** |

Lệch >±25% → bị trừ điểm khi chấm.

---

## Quick start (3 bước)

1. **Instructions:** dán toàn bộ khối giữa hai vạch ▼▲ trong [`SYSTEM-PROMPT.md`](SYSTEM-PROMPT.md).
2. **Knowledge:** upload 6 file `.md` trong [`knowledge/`](knowledge/).
3. **Brief:** chạy `python tools/get-brief.py mui C11` rồi dán brief vào cuộc hội thoại.

**Câu lệnh viết bài:**
```
Viết bài "Sửa mũi hỏng lần 2, lần 3 có được không?" — cụm C11 line Mũi,
dạng Bài tình huống. Brief đính kèm bên dưới.
```

---

## Đầu ra

Mỗi lần xuất gồm 4 phần, đúng thứ tự:

1. **PHIẾU BÀN GIAO** — cụm · tầng · giai đoạn · dạng bài · độ dài · trang đích · nỗi sợ đã giải · góc hỏi đã phủ (n/8) · số liệu + trạng thái xác minh · rào pháp lý · **tự chấm __/100**
2. **BÀI VIẾT** — Markdown, đúng khung của dạng bài
3. **KHỐI KỸ THUẬT** — meta title ≤60 ký tự · meta description ≤155 · slug · JSON-LD
4. **GHI CHÚ CHO PHÁP CHẾ** — từng điểm cần duyệt kèm mã rào

**Chỉ nộp khi tự chấm ≥85 và không có tiêu chí nhóm E nào bằng 0.**

---

## Công cụ

```bash
pip install openpyxl

python tools/get-brief.py --sets              # liệt kê 17 bộ dịch vụ
python tools/get-brief.py mui --list          # 15 cụm của bộ Mũi
python tools/get-brief.py mui C11             # brief đầy đủ cụm C11
python tools/get-brief.py Sacto C06 --core    # chỉ truy vấn CORE 80/20
python tools/get-brief.py mui C11 -o brief.md # ghi ra file
```

Brief xuất ra gồm: hành vi khách của giai đoạn (đang nghĩ gì · **nỗi sợ chi phối** · khát khao · trigger · Kangnam phải có gì) · góc hỏi cần phủ · rào pháp lý · từng truy vấn kèm **khối trả lời cần có**.

---

## Tài liệu

| File | Nội dung |
|---|---|
| [SYSTEM-PROMPT.md](SYSTEM-PROMPT.md) | Bộ não Agent — dán vào Instructions |
| [knowledge/cpw-quy-trinh-viet.md](knowledge/cpw-quy-trinh-viet.md) | 9 bước từ brief đến nộp bài |
| [knowledge/cpw-khung-bai-viet.md](knowledge/cpw-khung-bai-viet.md) | Khung xương 11 dạng bài · luật viết đoạn · schema |
| [knowledge/cpw-rubric-geo.md](knowledge/cpw-rubric-geo.md) | Rubric 100 điểm — **dùng chung với CPWCheck** |
| [knowledge/geo-phuong-phap-luan.md](knowledge/geo-phuong-phap-luan.md) | Trục 6 bước · S1–S6 · 80/20 *(đồng bộ từ GEO-Plant)* |
| [knowledge/kangnam-brand-geo.md](knowledge/kangnam-brand-geo.md) | Kangnam là ai · cơ sở · bác sĩ *(đồng bộ)* |
| [knowledge/geo-rao-phap-ly.md](knowledge/geo-rao-phap-ly.md) | 12 rào R0–R11 *(đồng bộ)* |
| [goi/](goi/) | **Bản gộp dự phòng** — 1 file thay cho 6 file rời, dùng khi chạm trần số file của nền tảng |
| [doc/01-cai-dat.md](doc/01-cai-dat.md) | Cài đặt · smoke test · xử lý sự cố |
| [doc/02-cau-lenh.md](doc/02-cau-lenh.md) | Công thức ra lệnh · prompt mẫu |
| [doc/03-output-mau.md](doc/03-output-mau.md) | Phiếu bàn giao mẫu · dấu hiệu bài đúng/sai |
| [doc/CHANGELOG.md](doc/CHANGELOG.md) | Lịch sử · việc còn treo |

> **File đồng bộ:** 5 file có ghi *(đồng bộ)* hoặc dùng chung được quản lý bởi
> `Agent-KN-GEO-Plant/tools/sync-shared-knowledge.py`. **Không sửa trực tiếp** — sửa ở file gốc rồi chạy script.

---

## Ranh giới

Không cam kết "100% · tuyệt đối · vĩnh viễn · không biến chứng · không đau · bảo hành trọn đời" (**R1**) · không nêu tên/hạ thấp đối thủ, **không phán xét nơi khách từng làm hỏng** (**R6**) · gắn đúng pháp nhân + phạm vi giấy phép (**R3**) · chỉ dùng bác sĩ **đã xác minh chuyên khoa** (**R4**) · ảnh/case khách phải có **văn bản đồng ý minh thị** (**R5**) · đánh dấu nội dung cần **GXNNDQC** (**R9**).

**Không bịa** số liệu · tỷ lệ · giá · tên bác sĩ · bằng cấp · số ca · case khách. Thiếu → `⚠ Cần xác minh từ Kangnam`, không lấp bằng chữ chung chung.

*Quyết định cuối luôn thuộc người dùng.*
"# Agent-KN-CPW" 
