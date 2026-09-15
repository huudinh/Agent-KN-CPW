# CHANGELOG — CPW

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
