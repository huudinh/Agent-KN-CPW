# QUY TRÌNH VIẾT — 9 BƯỚC TỪ BRIEF ĐẾN NỘP BÀI

Version: 1.0 · CPW **không được bỏ bước**. Thiếu dữ liệu ở bước nào thì ghi giả định ở bước đó, không nhảy cóc.

---

# BƯỚC 1 — NHẬN DIỆN CỤM

Xác định 5 thông tin, lấy từ bộ truy vấn của dịch vụ (`doc/BotruyvanGEO/<bộ>.xlsx`):

| Thông tin | Lấy ở đâu |
|---|---|
| Mã cụm + tên cụm | sheet 3 cột **CỤM CHỦ ĐỀ**, hoặc sheet 4 cột **MÃ / TÊN CỤM** |
| Tầng ưu tiên (A/B/C/D) | sheet 4 cột **TẦNG** |
| Giai đoạn S1–S6 | sheet 3 cột **GIAI ĐOẠN** |
| Trang đích | sheet 4 cột **TRANG ĐÍCH CHÍNH** |
| Dạng bài + số bài cần | sheet 4 cột **DẠNG NỘI DUNG CẦN SẢN XUẤT** |

**Không có bộ truy vấn?** → dùng `geo-bo-truy-van-index.md` để tra cụm, và nói rõ brief chi tiết còn thiếu.

---

# BƯỚC 2 — ĐỌC NỖI SỢ TRƯỚC KHI ĐỌC DỊCH VỤ

Mở sheet `2. <DV>- Hanh vi KH`, đọc đúng dòng giai đoạn của cụm. Ghi ra 4 dòng trước khi viết bất kỳ chữ nào:

```
Khách đang nghĩ gì:  ...
Nỗi sợ chi phối:     ...
Khát khao thật:      ...
Kangnam phải có gì:  ...
```

> **Đây là bước quyết định chất lượng bài.** Bỏ bước này thì bài sẽ thành bài giới thiệu dịch vụ — đúng thứ phương pháp luận cấm.

---

# BƯỚC 3 — LẤY BRIEF TRUY VẤN

Từ sheet 3, lọc các dòng thuộc cụm, lấy:

- **TRUY VẤN KHÁCH GÕ VÀO AI** → dùng làm H2/H3 (nguyên văn khi có thể)
- **GÓC HỎI (fan-out)** → kiểm tra bài phủ đủ góc chưa
- **KHỐI TRẢ LỜI CẦN CÓ** → đây chính là brief nội dung, viết theo đúng yêu cầu này
- **TỪ KHOÁ ƯU TIÊN** → dùng tự nhiên, **không nhồi**
- **RÀO PHÁP LÝ** → mã R0–R11 phải xử lý

Ví dụ brief thật (cụm C11 line Mũi):

> *Truy vấn:* "Sau khi nâng mũi hỏng bao lâu thì được sửa lại?"
> *Góc hỏi:* Thời gian · *Khối trả lời cần có:* "Mốc chuẩn: tối thiểu 3–6 tháng để mô ổn định, trừ trường hợp cấp (nhiễm trùng, lộ sụn, hoại tử) phải can thiệp ngay — phân định cấp/không cấp là nội dung AI trích rất nhiều"
> *Rào:* R9 · *Trang đích:* Trang con Khắc phục mũi hỏng

---

# BƯỚC 4 — CHỌN DẠNG BÀI & CHỐT ĐỘ DÀI

Tra `cpw-khung-bai-viet.md` §2. Ghi rõ: dạng bài · độ dài mục tiêu · nhóm sản xuất (A1/A2/B/C/D).
Lệch >±25% dải chuẩn sẽ bị trừ điểm khi chấm.

---

# BƯỚC 5 — DỰNG DÀN Ý THEO GÓC HỎI

Lập bảng kiểm trước khi viết:

| Góc hỏi | Tỷ trọng kho | Có trong bài? | H2 tương ứng |
|---|---|---|---|
| 4 Trường hợp áp dụng | 24,6% | | |
| 3 Hướng dẫn & quy trình | 19,1% | | |
| 5 Phản đối & rủi ro | 15,1% | | |
| 1 Định nghĩa & nguyên nhân | 11,1% | | |
| 6 Thực thể & kiểm chứng | 9,7% | | |
| 2 So sánh & lựa chọn | 8,3% | | |
| 7 Chi phí & chỉ số | 7,8% | | |
| 8 Địa phương | 4,1% | | |

**Bài trụ phải phủ ≥6/8 góc. Bài thường ≥3 góc, bắt buộc gồm góc chính của cụm.**
Ba góc *Trường hợp áp dụng · Hướng dẫn · Rủi ro* chiếm gần **59%** truy vấn — bỏ trống cả ba là trượt.

---

# BƯỚC 6 — VIẾT

Thứ tự viết đúng như sau, **không viết mở bài trước**:

1. **Viết khối TL;DR** (60–80 từ) — trả lời trọn vẹn câu H1. Đây là đoạn AI trích nhiều nhất.
2. **Viết câu BLUF của từng H2** — toàn bộ câu mở đầu trước, đọc lướt xem có tự đứng được không.
3. **Viết khối rủi ro/giới hạn** — viết sớm, đừng để cuối, vì đây là nơi dễ bị viết cho có.
4. **Viết phần thân còn lại.**
5. **Viết mở bài cuối cùng** — nêu nỗi sợ bằng lời khách trong 150 từ đầu.

**Sáu quy tắc bắt buộc khi viết:**

| # | Quy tắc | Căn cứ |
|---|---|---|
| ① | **BLUF** — câu đầu mỗi mục là câu trả lời đứng độc lập | AI trích theo đoạn, không theo bài |
| ② | **CÓ SỐ** — số kèm mốc/điều kiện | Nội dung có số hiển thị cao hơn **30–40%** |
| ③ | **PHỦ GÓC HỎI** | AI bung 1 câu hỏi thành **8–20 truy vấn con** |
| ④ | **DÁM NÓI ĐIỀU BẤT LỢI** | Nội dung cân bằng được đánh giá là nguồn khách quan, trích nhiều hơn hẳn |
| ⑤ | **NGÀY CẬP NHẬT + BS THẨM ĐỊNH** | Điều kiện của schema y khoa |
| ⑥ | **KHÔNG NHỒI TỪ KHOÁ** | Nhồi từ khoá cho kết quả **thấp hơn mức nền** |

---

# BƯỚC 7 — GẮN THỰC THỂ & KỸ THUẬT

- Nêu **đúng pháp nhân** thực hiện dịch vụ + cơ sở + phạm vi giấy phép của cơ sở đó.
- Bác sĩ: chỉ gắn tên **đã xác minh chuyên khoa**. Chưa xác minh → ghi `⚠ Cần xác minh chuyên khoa (KF-02) trước khi đăng`, **không tự điền tên**.
- Chèn JSON-LD đúng loại (xem `cpw-khung-bai-viet.md` §6).
- Liên kết: → trang trụ cụm · → 2–3 bài ngang cụm · → **đúng 1** cross-sell gợi mở.

---

# BƯỚC 8 — TỰ SOÁT RÀO PHÁP LÝ

Quét bản thảo, tìm và xử lý:

| Tìm | Thay bằng |
|---|---|
| "100%" · "tuyệt đối" · "vĩnh viễn" · "không biến chứng" · "không đau" · "bảo hành trọn đời" | "chế độ theo dõi và chỉnh sửa theo chính sách" · "kết quả tuỳ cơ địa và được bác sĩ đánh giá riêng" |
| Tên đối thủ · "nơi khác làm hỏng" | Bộ tiêu chí khách quan để khách tự đánh giá |
| Ảnh/case khách | Ghi rõ đã có **văn bản đồng ý minh thị**, nếu chưa → gỡ |
| Tên bác sĩ chưa xác minh | `⚠ Cần xác minh chuyên khoa (KF-02)` |
| Nội dung quảng cáo dịch vụ KCB | Đánh dấu `⚠ Cần GXNNDQC — Sở Y tế (R9)` |

---

# BƯỚC 9 — TỰ CHẤM THEO RUBRIC RỒI MỚI NỘP

Chấm bản thảo bằng `cpw-rubric-geo.md`. **Chỉ nộp khi tự chấm ≥85 và không có tiêu chí E nào bằng 0.**

Nộp kèm **PHIẾU BÀN GIAO**:

```
PHIẾU BÀN GIAO BÀI
Cụm: <mã + tên>          Tầng: <A/B/C/D>      Giai đoạn: <S_>
Dạng bài: <...>          Độ dài: <số từ> (chuẩn: <dải>)
Trang đích: <URL>        Từ khoá ưu tiên: <...>
Nỗi sợ đã giải: <...>
Góc hỏi đã phủ: <n/8> — <liệt kê>
Số liệu dùng trong bài: <liệt kê> — trạng thái xác minh: <...>
Rào pháp lý cần duyệt: <R_, R_>
Tự chấm: __/100
Còn thiếu / cần Kangnam cung cấp: <...>
```

---

# QUY TẮC VÀNG

> **Viết xong một bài, tự hỏi: "Nếu cắt tên Kangnam ra khỏi bài này, nó còn hữu ích với khách không?"**
> Câu trả lời phải là **CÓ**. Nếu bài chỉ hữu ích khi có tên thương hiệu, đó là bài quảng cáo — không phải bài GEO.
