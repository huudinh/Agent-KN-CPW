# TRI THỨC CPW — Kangnam Content Production Writer
> File này gộp **6 module tri thức** từ `knowledge/`. Sinh tự động ngày 2026-10-22 bằng `python tools/gop-tham-khao.py`.
> ⛔ **Không sửa file này** — sửa ở bản rời trong thư mục nguồn rồi chạy lại lệnh trên.

**Cách đọc:** mỗi phần bắt đầu bằng dòng `===== tên file =====` và là **một đơn vị tri thức riêng**. Tham chiếu dạng `[[tên-file]]` trong văn bản trỏ tới **phần cùng tên ngay trong file này**, không phải file bên ngoài.

## MỤC LỤC

| # | File | Cỡ |
|---|---|---|
| 1 | `cpw-khung-bai-viet.md` | 9.9 KB |
| 2 | `cpw-quy-trinh-viet.md` | 7.0 KB |
| 3 | `cpw-rubric-geo.md` | 11.6 KB |
| 4 | `geo-phuong-phap-luan.md` | 16.0 KB |
| 5 | `geo-rao-phap-ly.md` | 6.4 KB |
| 6 | `kangnam-brand-geo.md` | 11.9 KB |


===== cpw-khung-bai-viet.md =====

# KHUNG BÀI VIẾT THEO DẠNG — CPW

Version: 1.0 · Độ dài và tỷ lệ trong file này **đo từ 1.363 đầu việc thật** trong checklist sản xuất của Kangnam, không phải con số ước lượng.

---

# 1. BỐN NHÓM SẢN XUẤT

| Nhóm | Mô tả | Số bài trong kho | Hệ số quy đổi |
|---|---|---|---|
| **A1** | Bài trụ / chuyên sâu | 381 | **1,5** |
| **A2** | Bài thường | 609 | **1,0** |
| **B** | FAQ ngắn | 86 | **0,5** |
| **C** | Trang chi nhánh / địa phương | 264 | **1,0** |
| **D** | Tài sản kèm (checklist tải về, khối nhúng) | 23 | **0,5** |

---

# 2. MƯỜI MỘT DẠNG BÀI — ĐỘ DÀI CHUẨN

Cột *Độ dài* là `min – trung vị – max` đo trên kho thật. Lệch quá **±25%** so với dải này bị trừ 5 điểm (rubric F).

| Dạng bài | Độ dài (từ) | Giai đoạn | Vai trò |
|---|---|---|---|
| **PILLAR / TRANG TRỤ** | 2.000 – **2.750** – 3.750 | S2 · S3 | Trang trụ của cụm, gom mọi bài con |
| **TRANG CHUYÊN BIỆT** | 2.750 – **3.250** – 3.250 | S3 | Chủ đề giá trị cao đối thủ né (sửa hỏng, tái phẫu thuật) |
| **BÀI PHÂN ĐỊNH** | 2.000 – **2.250** – 2.250 | S3 | "Spa hay bệnh viện", "công hay tư" — trả bằng tiêu chí khách quan |
| **BÀI TÌNH HUỐNG** | 1.400 – **2.000** – 2.750 | S3 · S5 | Một tình huống hỏng/sự cố cụ thể |
| **BÀI Y KHOA / CHUYÊN SÂU** | 1.400 – **2.000** – 2.750 | S2 | Trục E-E-A-T, đổi cách AI phân loại Kangnam |
| **BÀI BIẾN CHỨNG** | 1.400 – **1.750** – 2.250 | S3 | Một biến chứng cụ thể, có sơ đồ |
| **TRANG CON** | 1.200 – **1.650** – 2.250 | mọi GĐ | Bài con trong cụm |
| **BÀI KIỂM CHỨNG** | 1.350 – **1.400** – 2.000 | S3 | Dạy khách tự kiểm chứng (giấy phép, sụn thật/giả, xem lọ) |
| **TRANG LOCAL / VỆ TINH** | 1.400 – **1.650** – 1.700 | S2 · S3 | Chi nhánh chuẩn NAP |
| **TRANG CHỨC NĂNG** | 1.000 – **1.750** – 1.750 | S3 | Bảng giá, đặt lịch |
| **TRANG THỰC THỂ** | 1.000 – **1.400** – 2.000 | S3 | Về Kangnam, hồ sơ bác sĩ, giấy phép |
| **FAQ NGẮN** | 500 – **600** – 800 | S5 · S6 | Một câu hỏi, một câu trả lời |

---

# 3. KHUNG XƯƠNG TỪNG DẠNG

## 3.1 PILLAR / TRANG TRỤ (2.750 từ)

```
H1  <Câu hỏi lớn nhất của cụm, đúng lời khách gõ>
    [Khối TL;DR — 60–80 từ, trả lời trọn vẹn câu H1, đây là đoạn AI trích nhiều nhất]
    [Hộp: Cập nhật <ngày> · Thẩm định chuyên môn: <chức danh + tên BS đã xác minh>]

H2  <Định nghĩa & nguyên nhân>            → góc hỏi 1
H2  <Bảng so sánh các lựa chọn>           → góc hỏi 2   [BẢNG — nêu cả nhược điểm]
H2  <Ai phù hợp, ai không phù hợp>        → góc hỏi 4   [quan trọng nhất: 24,6% truy vấn]
H2  <Quy trình từng bước có mốc thời gian>→ góc hỏi 3
H2  <Rủi ro & giới hạn — nói thật>        → góc hỏi 5   [BẮT BUỘC, có số liệu]
H2  <Chi phí: dải min–max, bóc tách cấu phần> → góc hỏi 7
H2  <Làm ở đâu: pháp nhân, cơ sở, phạm vi giấy phép> → góc hỏi 6 + 8
H2  Câu hỏi thường gặp                     [FAQPage schema, 5–8 câu]

[Khối liên kết: các bài con trong cụm]
[Khối cross-sell — ĐÚNG 1 hướng, giọng gợi mở]
[JSON-LD: MedicalWebPage + FAQPage + BreadcrumbList]
```

## 3.2 TRANG CHUYÊN BIỆT — sửa hỏng / tái phẫu thuật (3.250 từ)

Đây là dạng bài **giá trị đơn cao nhất và đối thủ né nhất**. Quy tắc riêng:

```
H1  <Tình trạng hỏng cụ thể + câu hỏi khách gõ>
    [TL;DR: nói thẳng làm được tới đâu, KHÔNG hứa về như ban đầu]

H2  Dấu hiệu nào là cấp, dấu hiệu nào chờ được   ← phân định cấp/không cấp
                                                    là nội dung AI trích rất nhiều
H2  Bao lâu thì sửa được, vì sao phải chờ         ← có mốc số cụ thể
H2  Các hướng xử lý theo mức độ                   ← phân tầng, không một-cỡ-cho-tất-cả
H2  Điều không thể khắc phục hoàn toàn            ← BẮT BUỘC, đây là điểm chiếm niềm tin
H2  Quy trình tiếp nhận ca tái phẫu thuật tại Kangnam
H2  Case thật                                     ← chỉ khi có VĂN BẢN ĐỒNG Ý (R5)
H2  Chi phí ca sửa khác ca làm mới thế nào
```

> **Tuyệt đối không phán xét nơi khách từng làm** (rào R6). Khách sửa hỏng đang xấu hổ, không đang tìm người để đổ lỗi.

## 3.3 BÀI BIẾN CHỨNG (1.750 từ)

```
H1  <Tên biến chứng + câu hỏi khách gõ>
    [TL;DR: có/không nguy hiểm · tỷ lệ gặp · xử lý được không]
H2  Biểu hiện thế nào, phân biệt với diễn tiến bình thường
H2  Vì sao xảy ra                                  ← cơ chế, không đổ cho khách
H2  Khi nào phải quay lại ngay                     ← KHỐI DẤU HIỆU BẤT THƯỜNG
H2  Xử lý thế nào, mất bao lâu
H2  Phòng ngừa từ khâu nào
```
Bắt buộc có **tỷ lệ gặp bằng số** hoặc `⚠ Cần xác minh từ Kangnam`.

## 3.4 BÀI PHÂN ĐỊNH (2.250 từ)

```
H1  <A hay B? — đúng câu khách gõ>
    [TL;DR: trả lời thẳng, nêu điều kiện áp dụng]
H2  Khác nhau ở đâu về mặt pháp lý & phạm vi chuyên môn
H2  BẢNG TIÊU CHÍ KHÁCH QUAN để khách tự đánh giá   ← linh hồn của dạng bài
H2  Trường hợp nào chọn A, trường hợp nào chọn B
H2  Cách tự kiểm chứng trước khi quyết định
```
> **Không nêu tên cơ sở nào** (R6). Đưa bộ tiêu chí, để khách tự chấm.

## 3.5 TRANG CHỨC NĂNG — BẢNG GIÁ (1.750 từ)

Cụm giá là **đòn rẻ và nhanh nhất** vì toàn ngành giấu giá.

```
H1  Bảng giá <dịch vụ> — cập nhật <ngày>
    [BẢNG: dải min–max theo từng hạng mục]
H2  Giá gồm những gì, không gồm những gì           ← bóc tách cấu phần
H2  Vì sao giá chênh nhau nhiều lần                ← giải thích, không công kích
H2  Cảnh báo giá rẻ bất thường                     ← nêu cơ chế, không nêu tên
H2  Trả góp & chính sách theo dõi sau
```
Bắt buộc: **ngày cập nhật** hiển thị rõ. Không có ngày = trang giá chết trong AI.

## 3.6 TRANG LOCAL / CHI NHÁNH (1.650 từ)

```
H1  <Dịch vụ> tại <Tỉnh/Thành> — <Tên cơ sở Kangnam>
    [Khối NAP: Tên pháp nhân · Địa chỉ đầy đủ · Điện thoại · Giờ làm việc]
H2  Cơ sở này làm được gì, KHÔNG làm gì            ← phạm vi giấy phép (R3)
    → viện tỉnh: tư vấn + tái khám; đại phẫu điều hướng về bệnh viện
H2  Đường đi & khu vực lân cận phục vụ
H2  Khách tỉnh xa: lịch trình mẫu, chỗ nghỉ, tái khám
H2  FAQ địa phương
[JSON-LD: MedicalClinic + địa chỉ + geo]
```
> Trang chi nhánh chiếm **>1/3 traffic AI** vào landing page. Đây là dạng bài có tỷ lệ hoàn vốn cao nhất.

## 3.7 FAQ NGẮN (600 từ)

```
H1  <Đúng nguyên văn câu khách hỏi>
    [Trả lời trọn vẹn trong 60–80 từ đầu — phần còn lại là mở rộng]
H2  Giải thích thêm
H2  Trường hợp ngoại lệ
[Link về trang trụ của cụm]
```

---

# 4. LUẬT VIẾT ĐOẠN — ÁP CHO MỌI DẠNG

| Luật | Chuẩn vận hành |
|---|---|
| **BLUF** | Câu đầu mỗi H2/H3 **là câu trả lời**, không phải dẫn dắt. Đọc riêng câu đó vẫn hiểu. |
| **Độ dài đoạn** | 40–70 từ. Đoạn >150 từ bị AI bỏ qua vì không trích gọn được. |
| **Không đại từ mồ côi** | Cấm mở đoạn bằng "Điều này", "Như trên", "Vấn đề đó". Nhắc lại danh từ. |
| **Một đoạn một ý** | Đoạn phải tự đứng được khi bị cắt khỏi bài. |
| **Heading là câu hỏi** | Ưu tiên dùng nguyên văn truy vấn khách gõ làm H2/H3. |
| **Số đi kèm điều kiện** | "Hết sưng sau 2 tuần khoảng 70%" ✅ · "hết sưng khá nhanh" ❌ |

---

# 5. KHỐI BẮT BUỘC CUỐI MỌI BÀI

```
─────────────────────────────────────────────
Cập nhật: <DD/MM/YYYY>
Thẩm định chuyên môn: <chức danh + tên BS đã xác minh chuyên khoa>
Nội dung mang tính tham khảo, không thay thế thăm khám trực tiếp.
Kết quả tuỳ cơ địa và được bác sĩ đánh giá riêng cho từng trường hợp.
─────────────────────────────────────────────
[Liên kết nội bộ: → trang trụ cụm · → 2–3 bài ngang cụm]
[Cross-sell: ĐÚNG 1 hướng, dạng gợi mở, không ép]
[CTA mềm: "Đăng ký tư vấn cùng bác sĩ" | "Đặt lịch thăm khám" | "Nhận phác đồ"]
```

**Cấm:** "Mua ngay" · "Chốt ngay" · "Kẻo hết" · "Ưu đãi cuối cùng".

---

# 6. SCHEMA JSON-LD THEO DẠNG BÀI

| Dạng bài | Schema |
|---|---|
| Pillar · Bài y khoa · Bài biến chứng · Bài tình huống | `MedicalWebPage` + `BreadcrumbList` |
| Bài có mục FAQ | thêm `FAQPage` |
| Trang thực thể / hồ sơ bác sĩ | `ProfilePage` + `Physician` + `sameAs` |
| Trang local / chi nhánh | `MedicalClinic` + `address` + `geo` + `openingHours` |
| Trang chức năng (bảng giá) | `WebPage` + `Offer` *(chỉ khi giá đã được duyệt công khai)* |
| Bài quy trình có các bước | thêm `HowTo` |

Mọi schema y khoa phải có `reviewedBy` trỏ đúng bác sĩ đã xác minh, và `dateModified` khớp ngày cập nhật hiển thị trên trang.


===== cpw-quy-trinh-viet.md =====

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


===== cpw-rubric-geo.md =====

# RUBRIC GEO — THANG CHẤM 100 ĐIỂM

Version: 1.0 · **File chuẩn dùng chung cho 2 Agent.**
`Agent-KN-CPW` viết **để đạt** rubric này · `Agent-KN-CPWCheck` chấm **theo đúng** rubric này.
Sửa rubric → phải cập nhật bản sao ở cả hai thư mục `knowledge/`.

---

# 0. NGUYÊN TẮC CHẤM

1. **Chấm bằng bằng chứng, không bằng cảm nhận.** Mỗi điểm trừ phải trích được câu/đoạn cụ thể trong bài.
2. **Không có điểm "cho qua".** Tiêu chí không kiểm chứng được từ bản thảo → chấm 0 và ghi lý do "không có dữ liệu để chấm".
3. **Nhóm E là cổng chặn.** Bất kỳ tiêu chí E nào bị 0 → **CHẶN XUẤT BẢN**, bất kể tổng điểm là bao nhiêu.
4. **Điểm trừ nhóm F không có sàn.** Bài 90 điểm nhưng nhồi từ khoá và trùng lặp nội bộ → còn 70.

---

# A · HÀNH TRÌNH & THẤU HIỂU KHÁCH HÀNG — 25 điểm

> Đây là nhóm quan trọng nhất. Bài viết hay về mặt câu chữ nhưng trả lời sai nỗi sợ của giai đoạn thì **mất khách dù dịch vụ tốt**.

| Mã | Tiêu chí | Điểm | Đạt tối đa khi | Chấm 0 khi |
|---|---|---|---|---|
| **A1** | **Định danh đúng giai đoạn S1–S6** | 5 | Bài ghi rõ giai đoạn mục tiêu và toàn bộ giọng văn, độ sâu, mức CTA khớp nhiệt độ của giai đoạn đó | Không xác định được giai đoạn, hoặc viết giọng S4 cho khách S1 |
| **A2** | **Trúng nỗi sợ chi phối** | 8 | Nỗi sợ của giai đoạn được gọi tên trong **150 từ đầu**, bằng chính lời khách, và toàn bài đi giải nỗi sợ đó | Bài không chạm nỗi sợ nào, hoặc chạm nỗi sợ của giai đoạn khác |
| **A3** | **Ngôn ngữ của khách** | 4 | Dùng từ khách gõ ("mũi bị bóng đỏ", "làm xong đậm hơn"), thuật ngữ y khoa luôn kèm giải thích ngay lần đầu | Viết bằng ngôn ngữ bệnh viện/marketing, thuật ngữ trần không giải thích |
| **A4** | **Trigger chuyển giai đoạn** | 4 | Cuối bài có đúng thứ khách cần để bước sang giai đoạn kế (bảng so sánh, checklist mang đi tư vấn, lịch trình theo ngày…) | Kết bài cụt, hoặc chỉ có CTA bán hàng |
| **A5** | **Không bán hàng sai giai đoạn** | 4 | S1–S2 giữ giọng giáo dục, CTA mềm cuối bài · S3–S4 mới được đưa offer/đặt lịch rõ | Nhồi CTA bán hàng vào bài kiến thức (đồng thời vi phạm rào **R0**) |

**Bản đồ nỗi sợ theo giai đoạn** — dùng để chấm A2:

| GĐ | Nhiệt | Nỗi sợ phải trả lời | Bài phải có |
|---|---|---|---|
| S1 | Cold | Sợ mình đang quá khắt khe · sợ bị đánh giá "thích làm màu" | Nội dung **định danh vấn đề**, không bán |
| S2 | Warm | Sợ chọn sai phương pháp · sợ bị tư vấn theo hướng đắt tiền | Bảng so sánh **nêu cả nhược điểm** |
| S3 | Warm→Hot | **SỢ HỎNG · SỢ CHỌN SAI BÁC SĨ · SỢ BỊ MOI TIỀN** | Rủi ro nói thật có số liệu · giá min–max · cách tự tra giấy phép |
| S4 | Hot | Sợ không thu xếp được việc/gia đình · sợ đau · sợ gây mê | Quy trình từng bước **có mốc thời gian** |
| S5 | Existing | Sợ mình là ca hỏng · sợ hỏi nhiều bị coi là phiền | Cẩm nang hậu phẫu **theo mốc ngày** + dấu hiệu bất thường |
| S6 | LTV | Sợ làm quá nhiều thành mặt giả | Cross-sell **gợi mở, đúng 1 hướng** |

---

# B · CẤU TRÚC ĐỂ AI TRÍCH DẪN — 25 điểm

> AI trích **theo đoạn, không theo bài**. Một bài hay nhưng không có đoạn nào đứng độc lập được thì không bao giờ được trích.

| Mã | Tiêu chí | Điểm | Đạt tối đa khi | Chấm 0 khi |
|---|---|---|---|---|
| **B1** | **BLUF mọi H2/H3** | 8 | **100%** heading có câu đầu là câu trả lời hoàn chỉnh, hiểu được khi tách khỏi ngữ cảnh | <50% heading đạt, hoặc mở đầu bằng dẫn dắt vòng vo |
| **B2** | **Phủ đủ góc hỏi** | 8 | Phủ đủ các góc hỏi mà brief của cụm yêu cầu; bài trụ phủ ≥6/8 góc | Chỉ đi một góc duy nhất |
| **B3** | **Đoạn trích được độc lập** | 5 | Đoạn 40–70 từ, không mở bằng đại từ mơ hồ ("điều này", "như trên"), tự đủ nghĩa | Đoạn dài >150 từ, phụ thuộc ngữ cảnh trước đó |
| **B4** | **Có cấu trúc quét được** | 4 | ≥1 bảng so sánh hoặc danh sách đánh số có tiêu đề rõ; câu hỏi khách gõ được dùng làm heading | Toàn bài là văn xuôi liền mạch |

**Phân bổ góc hỏi thật** — đo trên **4.311 truy vấn** của 17 bộ. Dùng để chấm B2 và để writer biết đầu tư vào đâu:

| # | Góc hỏi (fan-out) | Tỷ trọng | Gồm các nhãn trong bộ truy vấn |
|---|---|---|---|
| 4 | **Trường hợp áp dụng** | **24,6%** | Điều kiện · Thời gian · Kết quả · Trải nghiệm |
| 3 | **Hướng dẫn & quy trình** | **19,1%** | Hướng dẫn · Quy trình · Xử lý · Chăm sóc |
| 5 | **Phản đối & rủi ro** | **15,1%** | Rủi ro · Phản đối · Cấp cứu · Biến chứng |
| 1 | Định nghĩa & nguyên nhân | 11,1% | Định nghĩa · Nguyên nhân |
| 6 | Thực thể & kiểm chứng | 9,7% | Thực thể · Kiểm chứng |
| 2 | So sánh & lựa chọn | 8,3% | So sánh |
| 7 | Chi phí & chỉ số | 7,8% | Chi phí · Chỉ số |
| 8 | Địa phương | 4,1% | Local |

> **Đọc ra ưu tiên:** gần **59%** truy vấn rơi vào 3 góc *Trường hợp áp dụng · Hướng dẫn · Rủi ro*. Bài nào bỏ trống cả ba góc này thì dù viết hay vẫn trượt B2.

---

# C · BẰNG CHỨNG & TÍNH TRUNG THỰC — 15 điểm

| Mã | Tiêu chí | Điểm | Đạt tối đa khi | Chấm 0 khi |
|---|---|---|---|---|
| **C1** | **Có số cụ thể** | 6 | Bài trụ ≥5 số · bài thường ≥3 số, mỗi số kèm mốc/điều kiện ("hết sưng sau 2 tuần khoảng 70%") | Không có số nào, hoặc chỉ có số trang trí ("hàng nghìn khách") |
| **C2** | **Dám nói điều bất lợi** | 5 | ≥1 khối nêu **giới hạn thật** của giải pháp, đặt ở vị trí đọc được (không giấu cuối bài) | Nội dung một chiều, chỉ toàn ưu điểm |
| **C3** | **Mỗi số có căn cứ** | 4 | Mỗi con số có nguồn, hoặc gắn `⚠ Cần xác minh từ Kangnam` nếu chưa có | Số liệu **tự bịa** không nguồn, không cảnh báo |

> Nội dung **có số liệu** được hiển thị trong câu trả lời AI cao hơn **30–40%** so với nội dung chung chung. Nội dung **cân bằng** (dám nói điều bất lợi) được AI đánh giá là nguồn khách quan và trích nhiều hơn hẳn nội dung một chiều.

---

# D · THỰC THỂ & KỸ THUẬT GEO — 15 điểm

| Mã | Tiêu chí | Điểm | Đạt tối đa khi | Chấm 0 khi |
|---|---|---|---|---|
| **D1** | **Neo thực thể Kangnam** | 4 | Nêu rõ **đúng pháp nhân** thực hiện + cơ sở + phạm vi giấy phép của cơ sở đó | Nói chung chung "Kangnam", không rõ cơ sở nào làm được gì |
| **D2** | **Ngày cập nhật + BS thẩm định** | 4 | Có ngày cập nhật và dòng `Thẩm định chuyên môn: [chức danh + tên]` với bác sĩ **đã xác minh** | Thiếu một trong hai, hoặc gắn bác sĩ chưa xác minh (kéo theo E2) |
| **D3** | **Schema JSON-LD** | 4 | Đúng loại schema cho dạng bài (`MedicalWebPage` · `FAQPage` · `ProfilePage` + `Physician` · `MedicalClinic` · `BreadcrumbList`) | Không có schema, hoặc schema sai loại |
| **D4** | **Liên kết nội bộ** | 3 | Link về trang trụ của cụm + link ngang trong cụm + **đúng 1** khối cross-sell gợi mở cuối bài | Không link, hoặc nhồi nhiều hướng cross-sell |

---

# E · TUÂN THỦ PHÁP LÝ — 20 điểm · **CỔNG CHẶN**

> Bất kỳ tiêu chí nào ở nhóm này bị **0 điểm** → bài **KHÔNG ĐƯỢC XUẤT BẢN**, kể cả khi tổng điểm ≥85. Check phải ghi rõ `⛔ CHẶN XUẤT BẢN`.

| Mã | Rào | Điểm | Chấm 0 khi phát hiện |
|---|---|---|---|
| **E1** | **R1 — Cam kết kết quả** | 6 | Xuất hiện "100%", "tuyệt đối", "vĩnh viễn", "không biến chứng", "không đau", "bảo hành trọn đời", "đẹp như ý hoặc hoàn tiền" |
| **E2** | **R3/R4 — Pháp nhân & bác sĩ** | 5 | Gắn dịch vụ vào cơ sở không có giấy phép tương ứng; nêu tên bác sĩ **chưa xác minh chuyên khoa**; quảng cáo bác sĩ tại cơ sở chưa đăng ký hành nghề |
| **E3** | **R5 — Hình ảnh khách hàng** | 3 | Dùng ảnh/case khách mà không ghi nhận đã có **văn bản đồng ý minh thị** |
| **E4** | **R6 — So sánh đối thủ** | 3 | Nêu tên, hạ thấp cơ sở khác; ám chỉ "nơi khác làm hỏng"; phán xét nơi khách từng làm |
| **E5** | **R9 — Giấy xác nhận QC** | 3 | Là nội dung quảng cáo dịch vụ KCB nhưng **không đánh dấu** cần xin GXNNDQC tại Sở Y tế |

---

# F · ĐIỂM TRỪ (không có sàn)

| Lỗi | Trừ | Nhận dạng |
|---|---|---|
| **Nhồi từ khoá** | **−10** | Từ khoá chính lặp bất thường, câu văn gượng vì phải chèn từ. *Nhồi từ khoá cho kết quả **thấp hơn mức nền** trong AI search* |
| **Giọng quảng cáo trong bài kiến thức** (R0) | −5 | Bài S1/S2 mà dồn CTA bán hàng, khoa trương |
| **Một chiều, không nêu giới hạn** | −5 | Không có bất kỳ câu nào nói điều bất lợi (chồng lên C2) |
| **Trùng lặp nội bộ / ăn thịt cụm khác** | −10 | Lặp nội dung của bài khác cùng cụm thay vì link sang |
| **Sai độ dài so với dạng bài** | −5 | Lệch >±25% so với dải chuẩn của dạng bài |

---

# G · NGƯỠNG & KẾT LUẬN

| Tổng điểm | Kết luận | Hành động |
|---|---|---|
| **≥ 85** | ✅ **ĐẠT — xuất bản** | Chuyển BS thẩm định → Pháp chế → phát hành |
| **70 – 84** | 🟡 **ĐẠT CÓ ĐIỀU KIỆN** | Sửa đúng các mục bị trừ rồi xuất; không cần viết lại |
| **55 – 69** | 🟠 **CHƯA ĐẠT** | Viết lại phần chính (thường là nhóm A hoặc B), giữ phần đạt |
| **< 55** | 🔴 **LOẠI** | Viết lại từ brief |
| **Bất kỳ E = 0** | ⛔ **CHẶN XUẤT BẢN** | Sửa vi phạm pháp lý trước, rồi mới chấm lại |

**Công thức:** `Tổng = A + B + C + D + E − F`

---

# H · BẢNG CHẤM CHUẨN (Check phải xuất đúng khung này)

```
┌ TỔNG: __/100 · KẾT LUẬN: [ĐẠT | ĐẠT CÓ ĐIỀU KIỆN | CHƯA ĐẠT | LOẠI | ⛔ CHẶN]
│
│ A · Hành trình & thấu hiểu KH        __/25
│   A1 Giai đoạn __/5   A2 Nỗi sợ __/8   A3 Ngôn ngữ __/4
│   A4 Trigger __/4     A5 Đúng giai đoạn __/4
│ B · Cấu trúc để AI trích dẫn         __/25
│   B1 BLUF __/8   B2 Góc hỏi __/8   B3 Đoạn trích __/5   B4 Cấu trúc __/4
│ C · Bằng chứng & trung thực          __/15
│   C1 Có số __/6   C2 Điều bất lợi __/5   C3 Căn cứ __/4
│ D · Thực thể & kỹ thuật GEO          __/15
│   D1 Thực thể __/4  D2 Ngày+BS __/4  D3 Schema __/4  D4 Link __/3
│ E · Tuân thủ pháp lý                 __/20   [cổng chặn]
│   E1 R1 __/6  E2 R3-R4 __/5  E3 R5 __/3  E4 R6 __/3  E5 R9 __/3
│ F · Điểm trừ                         −__
└
```


===== geo-phuong-phap-luan.md =====

# PHƯƠNG PHÁP LUẬN GEO — KANGNAM

Version: 1.0 · Đây là **xương sống tư duy** của Agent. Mọi kế hoạch GEO phải đi đúng trục này, không đảo bước, không bỏ bước.

---

# 0. TUYÊN NGÔN — VÌ SAO KHÔNG GIỚI THIỆU VỀ MÌNH

> **Kangnam không đi kể chuyện mình giỏi. Kangnam đi theo hành trình của khách, gỡ từng nỗi lo, rồi mới xuất hiện như giải pháp.**

| Cách cũ (brand-first) | Cách của bộ này (customer-journey-first) |
|---|---|
| "Kangnam là bệnh viện thẩm mỹ hàng đầu…" | "Nâng mũi bị bóng đỏ đầu mũi thì khắc phục thế nào?" |
| Nội dung xoay quanh **chúng tôi có gì** | Nội dung xoay quanh **khách đang sợ gì** |
| Đo bằng thứ hạng từ khoá | Đo bằng **AI có trích dẫn Kangnam không** |
| Viết bài theo danh mục dịch vụ | Viết bài theo **cụm truy vấn thật khách gõ vào AI** |
| Né chủ đề rủi ro, biến chứng, giá | **Chiếm lĩnh** chủ đề rủi ro, biến chứng, giá — vì đó là nơi khách quyết định |

**Hệ quả vận hành:** thứ tự ưu tiên nội dung KHÔNG theo doanh thu dịch vụ, mà theo **điểm ưu tiên của cụm truy vấn** — nơi nỗi sợ lớn nhất gặp cơ hội GEO lớn nhất. Vì vậy cụm "Sửa mũi hỏng" và "Rủi ro & biến chứng" luôn đứng trên cụm "Các phương pháp nâng mũi".

---

# 1. TRỤC 6 BƯỚC (BẮT BUỘC, KHÔNG ĐẢO THỨ TỰ)

```
① Chọn lĩnh vực  →  ② Đối tượng KH  →  ③ Giai đoạn hành trình (S1–S6)
        →  ④ Cụm truy vấn (từ khoá)  →  ⑤ Cụm nội dung (bài viết)  →  ⑥ GEO/SEO
```

| Bước | Làm gì | Nguồn dữ liệu | Đầu ra |
|---|---|---|---|
| ① **Chọn lĩnh vực** | Chốt phạm vi: thương hiệu tổng, PTTM, Béo, Da, Wellness, Nha khoa, quốc tế | `geo-bo-truy-van-index.md` — 17 bộ | Danh sách bộ dịch vụ đưa vào kế hoạch |
| ② **Đối tượng KH** | Xác định nhóm khách của từng bộ (8–10 nhóm/bộ) | sheet `2. <DV>- Hanh vi KH` | Chân dung + nỗi sợ chi phối |
| ③ **Giai đoạn** | Rải đối tượng lên 6 giai đoạn S1→S6, xác định giai đoạn quyết định | sheet 2, cột GIAI ĐOẠN | Trọng số nỗ lực theo giai đoạn |
| ④ **Cụm truy vấn** | Lấy cụm C01–C15 + số truy vấn + điểm ưu tiên + tầng 80/20 | sheet `3. <DV>- Bo truy van Master` | Danh sách cụm xếp hạng |
| ⑤ **Cụm nội dung** | Quy cụm → số bài, dạng bài, trang đích, sóng, người phụ trách | sheet `4. <DV>- Ban do noi dung` | **Khối lượng sản xuất** (đơn vị: bài) |
| ⑥ **GEO/SEO** | Gắn KPI đo được: prompt đo GEO, top từ khoá, traffic AI, lead | sheet `5. <DV>- Prompt do luong` + `template/GEO-KANGNAM-2026.xlsx` | 2 TAB Excel: KPI + Công việc triển khai |

**Quy tắc vàng:** không được nhảy từ ① sang ⑤. Mọi bài viết trong kế hoạch phải truy ngược được về **một cụm truy vấn**, cụm đó phải truy ngược được về **một giai đoạn**, giai đoạn đó phải truy ngược được về **một nỗi sợ của một đối tượng thật**. Bài nào không truy ngược được → loại khỏi kế hoạch.

---

# 2. BƯỚC ③ — 6 GIAI ĐOẠN HÀNH TRÌNH (S1–S6)

Đây là khung dùng chung cho cả 17 bộ. Mỗi giai đoạn có **một nỗi sợ khác nhau** — trả lời sai nỗi sợ thì mất khách dù dịch vụ tốt.

| GĐ | Tên | Nhiệt | Khách đang nghĩ gì | Nội dung Kangnam phải có | Vai trò trong kế hoạch |
|---|---|---|---|---|---|
| **S1** | NHẬN BIẾT | Cold · ★ | "Có gì đó không ổn nhưng không biết gọi là gì" | Nội dung **định danh vấn đề**, không bán hàng | Cửa vào rộng — traffic, không tính chuyển đổi |
| **S2** | TÌM HIỂU | Warm · ★★ | "Có bao nhiêu cách? Cái nào hợp với tôi?" | Bảng so sánh **trung thực, nêu cả nhược điểm** | Xây E-E-A-T, đổi cách AI phân loại Kangnam |
| **S3** | CÂN NHẮC & NỖI SỢ | Warm→Hot · ★★★ | "Có nguy hiểm không? Hết bao nhiêu? Làm ở đâu an toàn?" | **Rủi ro nói thật có số liệu · bảng giá công khai · cách tự kiểm tra giấy phép · case thật** | ⚠ **ĐIỂM QUYẾT ĐỊNH — chiếm ~50% điểm ưu tiên toàn bộ. Luôn ưu tiên tuyệt đối.** |
| **S4** | THỰC HIỆN | Hot · ★★ | "Cần chuẩn bị gì? Nghỉ mấy ngày?" | Quy trình từng bước **có mốc thời gian** | Giảm huỷ lịch, tăng show-up rate |
| **S5** | TRẢI NGHIỆM & HẬU PHẪU | Existing · ★★ | "Sưng thế này có bình thường không?" | Cẩm nang hậu phẫu **theo mốc ngày** | Không tạo lead mới nhưng **neo thực thể** trong AI + giảm biến chứng + tạo khách giới thiệu |
| **S6** | GẮN BÓ & MỞ RỘNG | LTV · ★ | "Mũi ổn rồi, giờ nhìn cằm lại thấy ngắn" | Cross-sell **gợi mở, mỗi bài một hướng** | Tăng LTV — biến một ca thành một hành trình |

**Phân bổ nỗ lực chuẩn theo giai đoạn** (dùng khi chưa có dữ liệu riêng): S3 ≈ 50% · S2 ≈ 20% · S1 ≈ 8% · S4 ≈ 8% · S5 ≈ 8% · S6 ≈ 6%.

**3 nỗi sợ nền của toàn ngành thẩm mỹ** — mọi bài phải trả lời được ít nhất một:
1. **Sợ hỏng không sửa được** — không phải sợ đau, mà sợ vĩnh viễn. Đối thủ né chủ đề này → Kangnam trả lời thẳng bằng số liệu + case tái phẫu thuật.
2. **Sợ chọn sai bác sĩ/cơ sở** — khách không đủ chuyên môn để đánh giá tay nghề, họ tìm thứ **kiểm chứng được**: giấy phép, chứng chỉ hành nghề, case cùng tình trạng.
3. **Sợ bị moi tiền** — giá mập mờ = tín hiệu bị lừa. Bảng giá công khai dải min–max vừa gỡ nỗi sợ vừa là vũ khí GEO mạnh nhất.

---

# 3. BƯỚC ④ — CỤM TRUY VẤN & CÔNG THỨC ƯU TIÊN

## 3.1 Vì sao không dùng bộ từ khoá SEO cũ

- Truy vấn vào AI dài gấp **~6 lần** truy vấn Google (≈23 từ so với 3–4 từ) — khách gõ nguyên một câu chuyện.
- AI "bung" (query fan-out) một câu hỏi thành **8–20 truy vấn con** rồi mới tổng hợp. Chỉ **32%** trích dẫn đến từ trang top 10 Google — **68%** đến từ trang ngoài top 10 nhưng khớp đúng một truy vấn con.
- **88%** thương hiệu KHÔNG được AI trích dẫn nếu chỉ tối ưu SEO truyền thống. Thương hiệu phủ được **>80% không gian chủ đề** giữ được **~85%** mức hiển thị trong AI.
- → Cuộc chơi không phải "lên top từ khoá", mà là **PHỦ KÍN KHÔNG GIAN CÂU HỎI** của một khách hàng, từ lúc soi gương đến lúc tái khám.

## 3.2 Công thức điểm ưu tiên (điểm tối đa 81)

```
ĐIỂM ƯU TIÊN = Giá trị DT × Nhiệt độ × Ưu tiên × Cơ hội GEO
               (Cao 3    (Hot 3     (P1 3     (1–3, lấy từ traffic AI
                TB  2     Warm 2     P2 2      thật của trang đích)
                Thấp 1)   Existing 2 P3 1)
                          Cold 1)
```

**Ngưỡng Cơ hội GEO** theo bằng chứng traffic AI của trang đích: ≥50 phiên → 3 · ≥5 phiên → 2 · còn lại (kể cả trang chưa có traffic) → 1. Trang cần tạo mới lấy mức mặc định theo nhóm mở rộng.

## 3.3 Bốn tầng 80/20 — quy tắc phân bổ ngân sách nội dung

| Tầng | Tên | % ngân sách | Thời điểm | Đặc điểm |
|---|---|---|---|---|
| **A** | CORE 80/20 | **70%** | 90 ngày đầu | ~5 cụm, ~33% truy vấn nhưng chiếm **~50–60% điểm ưu tiên**. Hầu hết nằm ở S3. |
| **B** | Đòn bẩy chuyển đổi | **20%** | Khi A xong ~60% | ~5 cụm — quy trình, vật liệu, cầu nối, nhóm đặc thù |
| **C** | Uy tín & giữ chân | **10%** | Chạy nền | ~3 cụm — y khoa E-E-A-T, hậu phẫu, cross-sell. Tái sử dụng qua Zalo OA/CSKH |
| **D** | Cửa vào rộng | **0% ngân sách mới** | Sau 90 ngày | ~2 cụm — chỉ viết pillar nền, tái sử dụng nội dung sẵn có |

## 3.4 Bảy nhóm mẫu thắng trong AI Search (bằng chứng traffic thật)

Dùng để quyết định **mở rộng truy vấn theo hướng nào** — đây là dữ liệu quan sát được, không phải giả định.

| Mã | Nhóm mở rộng | Mẫu thắng quan sát được | Cách mở rộng |
|---|---|---|---|
| G1 | Thực thể thương hiệu | Trang chủ là landing #1 (582 phiên AI) khi khách hỏi "Kangnam có uy tín không" | Mỗi câu kiểm chứng thương hiệu → 1 khối trả lời trên trang thực thể + FAQPage schema |
| G2 | Chi nhánh × Dịch vụ × Tỉnh | Trang chi nhánh chiếm **>1/3** traffic AI vào landing page | Ma trận 9 cơ sở × dịch vụ trọng điểm; ưu tiên HN, SG, Đà Nẵng, Thanh Hoá |
| G3 | Bác sĩ | ~25 hồ sơ bác sĩ nhận gần 190 phiên AI | Xác minh chuyên khoa → gắn bác sĩ vào dịch vụ → ProfilePage/Physician schema |
| G4 | Giá & chi phí | Ý định lớn thứ hai sau địa điểm; AI trích bài **có con số** | Mỗi dịch vụ 1 trang giá chuẩn: dải min–max, bóc tách cấu phần, ngày cập nhật, trả góp |
| G5 | So sánh bệnh viện công / cơ sở khác | AI dẫn khách hỏi "hút mỡ BV 108 giá" về Kangnam → AI coi Kangnam là **nguồn so sánh** | Viết theo khung tiêu chí khách quan công–tư, **không nêu tên hạ thấp** |
| G6 | Hậu phẫu & sự cố | Câu hậu phẫu được Perplexity/Claude trích mạnh — nguồn AI ngoài ChatGPT | Phủ mốc hồi phục + dấu hiệu bất thường + sửa lại cho 5 dịch vụ PTTM |
| G7 | Chuyên khoa & cầu nối hệ sinh thái | Trang chuyên khoa bắt đầu có traffic AI | Mỗi dịch vụ gợi **MỘT** bước tiếp theo; lấp Nha khoa & Weight Loss đang gần như vắng AI |

---

# 4. BƯỚC ⑤ — 6 QUY TẮC VIẾT ĐỂ ĐƯỢC AI TRÍCH DẪN

Bắt buộc với mọi bài trong kế hoạch. Khi Agent mô tả đầu việc nội dung, phải nhắc được các quy tắc này trong cột công việc chi tiết.

1. **BLUF** — câu đầu tiên của mỗi mục PHẢI là câu trả lời đứng độc lập, hiểu được khi tách khỏi ngữ cảnh. *AI trích theo đoạn, không trích theo bài.*
2. **CÓ SỐ** — nội dung có số liệu được hiển thị trong câu trả lời AI cao hơn **30–40%**. "Hết sưng sau 2 tuần khoảng 70%" thắng "hết sưng khá nhanh".
3. **PHỦ 8 GÓC HỎI** cho mỗi chủ đề: định nghĩa · so sánh · hướng dẫn · trường hợp áp dụng · phản đối/rủi ro · thực thể liên quan · chi phí/chỉ số · địa phương. *Đây chính là 8 hướng AI bung truy vấn.*
4. **DÁM NÓI ĐIỀU BẤT LỢI** — "không thể về y hệt ban đầu", "da dày khó có đầu mũi thanh mảnh". Nội dung cân bằng được AI đánh giá là nguồn khách quan và trích nhiều hơn hẳn nội dung một chiều.
5. **GHI NGÀY CẬP NHẬT + TÊN BÁC SĨ THẨM ĐỊNH** trên mọi bài y khoa (schema ProfilePage / IndividualPhysician).
6. **KHÔNG NHỒI TỪ KHOÁ** — nhồi từ khoá cho kết quả **thấp hơn mức nền** trong AI search. Viết như đang trả lời một người thật.

**Quy đổi khối lượng sản xuất** (dùng khi quy bài ra nhân lực):

| Nhóm | Mô tả | Độ dài | Hệ số quy đổi |
|---|---|---|---|
| A1 | Bài trụ / chuyên sâu / trang pillar | 2.000–2.750 từ | **1.5** |
| A2 | Bài thường / bài tình huống / FAQ dài | 1.400–1.750 từ | **1.0** |
| A3 | Trang local, FAQ ngắn, khối nội dung nhúng | <1.400 từ | **0.5** |

---

# 5. BƯỚC ⑥ — ĐO LƯỜNG GEO (KPI THAY THẾ THỨ HẠNG TỪ KHOÁ)

## 5.1 Share of Voice trong AI — KPI trung tâm

**Cách chạy:** chế độ **ẩn danh** (không đăng nhập, tắt cá nhân hoá), dán nguyên văn từng prompt vào **ChatGPT · Gemini · Google AI Overview**. Ghi `1` nếu Kangnam được nhắc tên, `0` nếu không. **Chạy 3 lần lấy đa số.** Nhân bản sheet đo mỗi tháng.

**Lưu ý bản chất:** kết quả AI thay đổi theo phiên (chỉ ~27% truy vấn con lặp lại giữa các lần) → **đo XU HƯỚNG theo tháng, không đo tuyệt đối một lần**.

Mỗi bộ dịch vụ có sẵn bộ prompt đo lường trong sheet `5. <DV>- Prompt do luong`, gắn với cụm và tầng. Ngoài ra hệ thống có 3 bộ prompt vận hành: **20 prompt chính · 8 prompt hub chi nhánh · 19 prompt tỉnh**.

## 5.2 Năm trụ cột KPI (khớp TAB KPI của file output)

| # | Trụ cột | Chỉ tiêu trọng tâm | Trọng số mặc định |
|---|---|---|---|
| 1 | Hạ tầng Web & Hub | Kiến trúc 5 line · cổng Hub liên kết · tải trang <2s | 0.10 |
| 2 | Sản lượng Bài viết | Số bài hoàn thành/tháng theo từng thương hiệu & line | 0.20 |
| 3 | SEO & GEO AI Search | Top 3/5/10 Google · tỷ lệ được nhắc trên ChatGPT/Gemini/AI Overview | 0.40 |
| 4 | Traffic | Organic traffic google.com.vn + **Traffic AI** (referral từ LLM) | 0.15 |
| 5 | Form Lead | Số lead · sđt xác nhận có nhu cầu · KH đến cửa | 0.15 |

**Trọng số đánh giá theo tháng** trong một quý 4 tháng: Setup 20% · Tăng tốc 25% · Đột phá 30% · Về đích 25%.

---

# 6. QUY TẮC LẬP KẾ HOẠCH THEO THÁNG

Khi người dùng nói "lập kế hoạch GEO cho N tháng, từ tháng X", Agent áp dụng:

## 6.1 Ánh xạ sóng → tháng

| Số tháng | Ánh xạ |
|---|---|
| 3 tháng | T1 = Sóng 1 (Tầng A) · T2 = Sóng 2 (Tầng B) · T3 = Sóng 3 (Tầng C) |
| 4 tháng | T1 Setup + Sóng 1 · T2 Sóng 1 (tiếp) + Sóng 2 · T3 Sóng 2 + Sóng 3 · T4 Sóng 3 + Nền |
| 6 tháng | Sóng 1 trải T1–T2 · Sóng 2 trải T3–T4 · Sóng 3 T5 · Nền T6 |
| 12 tháng | Quý 1 Sóng 1 · Quý 2 Sóng 2 · Quý 3 Sóng 3 · Quý 4 Nền + nhân bản chi nhánh/tỉnh |

## 6.2 Bốn giai đoạn của một chu kỳ (đặt tên cho từng tháng)

**Setup → Tăng tốc → Đột phá → Về đích.** Tháng Setup luôn gồm: khoá bộ đo GEO lấy mốc gốc, audit từ khoá, thiết lập GA4 + heatmap, ban hành khung loại bài, gắn thẻ tagging theo hành trình.

## 6.3 Bảy nguyên tắc phân bổ sản lượng

1. **Tầng A trước** — không mở Tầng B khi Tầng A chưa xong ~60%.
2. **S3 trước S1** — luôn xuất bản cụm nỗi sợ/giá/chọn cơ sở trước cụm nhận biết.
3. **Tháng nào cũng chạy đủ các line trọng điểm** — không dồn hết một line vào một tháng.
4. **Sản lượng phẳng** — chênh lệch giữa tháng cao nhất và thấp nhất ≤25%, trừ tháng Setup được phép thấp hơn.
5. **80/20 theo tầng** — tầng 1–6 làm trong chu kỳ, tầng 7–9 đẩy sang backlog kỳ sau.
6. **Trang chi nhánh** chỉ làm **8 hub chính** (Hà Nội · TP.HCM · Hải Phòng · Nghệ An · Đà Nẵng · Cần Thơ · Bình Dương · Thanh Hoá), rải đều ~2 trang/tháng. **19 trang tỉnh vệ tinh KHÔNG nằm trong phạm vi quý.**
7. **Mỗi đầu việc nội dung phải có người phụ trách và hạn chót cuối tháng** — không để trống.

## 6.4 Quy tắc số liệu

- Chỉ tiêu sản lượng: **tính được** từ `geo-bo-truy-van-index.md` → được phép đưa số cụ thể.
- Chỉ tiêu SEO/GEO/Traffic/Lead: **phải có số hiện tại làm mốc**. Nếu người dùng chưa cung cấp → ghi `⚠ Cần xác minh từ Kangnam` ở cột "Hiện tại", đề xuất **mức tăng trưởng tương đối** (%), **KHÔNG bịa số tuyệt đối**.
- Mọi con số/case/giá/lịch bác sĩ phải xác minh trước khi chạy.


===== geo-rao-phap-ly.md =====

# RÀO PHÁP LÝ GEO — SOÁT TRƯỚC KHI ĐƯA ĐẦU VIỆC VÀO KẾ HOẠCH

Version: 1.0 · Trích KF-11 (pháp luật cập nhật đến 7/2026). **Tài liệu nội bộ, không thay thế ý kiến Pháp chế.**

> **Nguyên tắc nền: KHÔNG CHẮC → DỪNG → HỎI PHÁP CHẾ → RỒI MỚI ĐĂNG.**

Mỗi truy vấn trong sheet `3. <DV>- Bo truy van Master` đã được gắn mã rào `R0`–`R11`. Khi Agent viết cột **Công việc chi tiết** của TAB 2, phải ghi mã rào tương ứng trong ngoặc để Pháp chế biết đường duyệt.

---

# 1. BẢNG 12 RÀO

| Mã | Rào | KHÔNG được làm | THAY BẰNG | Người duyệt |
|---|---|---|---|---|
| **R0** | Thấp — nội dung kiến thức | Quảng cáo dịch vụ trong bài kiến thức; CTA bán hàng dồn dập | Giữ giọng giáo dục; CTA mềm cuối bài; vẫn ghi ngày cập nhật + bác sĩ thẩm định | Content lead |
| **R1** | **Cam kết kết quả** | "Cam kết đẹp 100%", "vĩnh viễn", "không biến chứng", "bảo hành trọn đời", "đẹp như ý hoặc hoàn tiền" | "Chế độ theo dõi và chỉnh sửa theo chính sách", "kết quả tuỳ cơ địa và được bác sĩ đánh giá riêng" | Pháp chế |
| **R2** | Danh mục kỹ thuật (DMKT) | Đăng dịch vụ/kỹ thuật không có trong DMKT của đúng pháp nhân; thổi phồng "công nghệ độc quyền" | Chỉ nêu kỹ thuật có trong DMKT; tên thương mại phải soi chiếu được về tên DMKT | Pháp chế + Chuyên môn |
| **R3** | **Đúng pháp nhân** | Một trang chạy chung nhiều pháp nhân mà không ghi rõ; đăng dịch vụ mình không có giấy phép để dẫn khách sang pháp nhân khác | Mỗi kênh và mỗi nội dung gắn **đúng pháp nhân có giấy phép**; dùng chung thì ghi rõ pháp nhân thực hiện từng dịch vụ | Pháp chế |
| **R4** | **Bác sĩ** | Gắn bác sĩ vào dịch vụ khi chưa xác minh chuyên khoa; quảng cáo bác sĩ tại cơ sở chưa đăng ký hành nghề | Chỉ dùng bác sĩ đã xác minh chuyên khoa + đăng ký hành nghề đúng cơ sở; author box `"Thẩm định chuyên môn: [chức danh + tên]"` | Chuyên môn + HR |
| **R5** | Hình ảnh khách hàng | Dùng ảnh/video khách khi mới có thoả thuận miệng; suy đoán "khách không phản đối"; dùng ngoài phạm vi đã đồng ý | **Văn bản đồng ý minh thị** nêu rõ: loại dữ liệu, mục đích marketing, kênh, thời hạn, quyền rút lại — lưu để xuất trình | CSKH + Pháp chế |
| **R6** | So sánh đối thủ | Nêu tên, so sánh trực tiếp, hạ thấp cơ sở khác; ám chỉ "nơi khác làm hỏng" | Đưa **bộ tiêu chí khách quan** để khách tự đánh giá; với khách sửa hỏng thì **tuyệt đối không phán xét nơi cũ** | Pháp chế |
| **R7** | Trang thiết bị & vật tư | Mượn hình máy nơi khác; thổi phồng công dụng; nêu vật tư cơ sở không thực sự có | Chỉ nêu thiết bị/vật tư cơ sở đang có, đúng tính năng và số lưu hành | Kho vật tư + Pháp chế |
| **R8** | Khách nước ngoài | Đăng nội dung tiếp nhận khách nước ngoài khi thiếu bất kỳ điều kiện nào trong 4 điều kiện bắt buộc | Đủ 4: dịch vụ trong DMKT · cơ sở đủ phạm vi chuyên môn · năng lực ngôn ngữ/phiên dịch được công nhận · văn bản đồng ý song ngữ | Pháp chế |
| **R9** | **Giấy xác nhận nội dung QC** | Phát hành nội dung quảng cáo dịch vụ KCB chưa xin GXNNDQC | Đến 7/2026 vẫn còn hiệu lực, thẩm quyền đã phân cấp về **SỞ Y TẾ**. Xác minh trực tiếp với Sở trước chiến dịch lớn | Pháp chế (Sở Y tế) |
| **R10** | KOL / người chuyển tải | KOL nói về dịch vụ mà không công khai là quảng cáo | Từ **01/01/2026** KOL phải xác minh tính trung thực, công khai `#quảng_cáo`, chịu trách nhiệm liên đới — ràng buộc trong hợp đồng | Brand + Pháp chế |
| **R11** | Người nổi tiếng | Nêu tên hoặc dùng hình người nổi tiếng; suy đoán họ đã phẫu thuật | Phân tích xu hướng chung, không cá nhân hoá | Brand + Pháp chế |

---

# 2. HAI RÀO CHI PHỐI KHỐI LƯỢNG LỚN NHẤT

Trong một bộ 262 truy vấn điển hình:

- **R9 (GXNNDQC)** chạm **88 truy vấn**, trong đó **36 CORE** → đây là nút thắt tiến độ lớn nhất. **Phải đưa việc "xin GXNNDQC" thành một đầu việc riêng trong kế hoạch tháng Setup**, không để đến lúc sắp đăng mới xin.
- **R1 (cam kết kết quả)** chạm **111 truy vấn**, trong đó 14 CORE → xử lý bằng **checklist từ cấm** áp cho toàn bộ đội content, không duyệt từng bài.

**Điểm nóng nhất: R3 (đúng pháp nhân)** — ít truy vấn (4) nhưng **100% là CORE**, và rơi đúng vào cụm C08 (Chọn cơ sở) + C14 (Thực thể) — hai cụm Tầng A của mọi bộ. Sai ở đây là sai ở nơi khách quyết định.

---

# 3. QUY TRÌNH BẮT BUỘC (đưa vào cột Công việc chi tiết như một đầu việc thường trực)

```
MKT/Chi nhánh soạn
   → tự kiểm checklist rào R0–R11
   → BS thẩm định chuyên môn
   → Pháp chế duyệt nội dung & hình ảnh
   → (nếu là quảng cáo dịch vụ KCB) xin GXNNDQC tại Sở Y tế
   → phát hành
   → lưu hồ sơ
```

**Hệ quả cho lập kế hoạch:** mọi đầu việc sản xuất nội dung phải cộng thêm **thời gian duyệt 2 lớp (BS + Pháp chế)** vào hạn chót. Không đặt hạn chót sản xuất trùng ngày phát hành.

---

# 4. BA CÂU CẤM TUYỆT ĐỐI (Agent tự soát mọi đầu ra)

1. Không cam kết **tuyệt đối / 100% / vĩnh viễn / không đau / không rủi ro / không biến chứng / bảo hành trọn đời**.
2. Không **tự tạo** số liệu · review · giá · voucher · chính sách · mức giảm · thông tin bác sĩ (bằng cấp, kinh nghiệm, giải thưởng, số ca).
3. Không **hạ thấp đối thủ**, không xem bệnh viện thẩm mỹ là spa, không lấy giảm giá làm trọng tâm.

Mọi con số, case, giá, lịch bác sĩ trong kế hoạch phải **xác minh trước khi chạy**. Thiếu → ghi `⚠ Cần xác minh từ Kangnam`, **không bịa để lấp bảng**.


===== kangnam-brand-geo.md =====

# KANGNAM — HỒ SƠ THƯƠNG HIỆU CHO GEO

Version: 1.0 · Agent đọc file này để biết **Kangnam là ai, làm gì, ở đâu, ai là bác sĩ** trước khi lập bất kỳ kế hoạch GEO nào.
Website chính thức: `benhvienthammykangnam.com.vn`

> **Quy ước:** thông tin có `⚠` là **chưa xác minh** — Agent được phép nhắc đến để đặt câu hỏi, nhưng **KHÔNG được đưa vào nội dung xuất bản hoặc vào ô số liệu của kế hoạch** cho đến khi Kangnam xác nhận.

---

# 1. ĐỊNH VỊ

> **KANGNAM — CHUẨN MỰC ĐẦU TƯ NHAN SẮC**

**Tuyên bố định vị:** *"Kangnam là điểm đến y khoa dành cho những khách hàng xem nhan sắc là một khoản đầu tư xứng đáng, cần được thực hiện chuẩn mực ngay từ đầu."*

**Vai trò:** người thiết lập chuẩn mực đầu tư nhan sắc tại Việt Nam — một **điểm đến y khoa**, KHÔNG phải spa làm đẹp. Đây là điểm phân định phải xuất hiện trong mọi nội dung GEO: khi AI được hỏi "spa hay bệnh viện", Kangnam phải nằm ở phía bệnh viện.

**Khác biệt cốt lõi:** Bác sĩ giỏi + Công nghệ tiên tiến + Tư duy đầu tư dài hạn.
**Phân khúc:** trung – cao cấp; cạnh tranh bằng giá trị, bác sĩ, công nghệ, kết quả — **KHÔNG bằng giá thấp**.

---

# 2. DOANH NGHIỆP

- **Tên:** Bệnh viện Thẩm mỹ Kangnam
- **Loại hình:** Bệnh viện chuyên khoa thẩm mỹ, mô hình đa chuyên khoa
- **Thành lập:** 2010 — một trong những đơn vị tiên phong phẫu thuật thẩm mỹ bài bản tại Việt Nam
- **Định hướng:** chuẩn bệnh viện thẩm mỹ công nghệ Hàn Quốc; an toàn – chuyên môn – đạo đức nghề nghiệp
- **Chương trình tiêu biểu:** *"Hành Trình Lột Xác"* (7 mùa) — minh chứng năng lực xử lý ca khó

---

# 3. HỆ SINH THÁI 5 BUSINESS LINE

Đây là 5 dòng thương hiệu dùng làm **trục phân nhóm KPI sản lượng** trong file output.

| Mã | Thương hiệu / Line | Phạm vi | Bộ truy vấn tương ứng |
|---|---|---|---|
| **KPS** | **Kangnam Plastic Surgery** | Phẫu thuật thẩm mỹ: Mũi · Mắt · Hàm mặt · Ngực · Hút mỡ (+ Cấy mỡ · Căng da · Môi) | `mui` `catmi` `hammat` `nguc` `hutmo` `caymo` `cangda` `moi` |
| **KBS** | **Kangnam Beauty & Spa** | Da liễu & trẻ hoá: Nám/sắc tố · Filler · Botox · Sẹo rỗ · Sẹo lồi · HIFU/RF/Thermage · Chăm sóc da · Xoá xăm | `Sacto` `Trehoa` `seo` `chamsocda` `lamday` `xoaxam` |
| **KWL** | **Kangnam Weight Loss** | Giảm mỡ đa chuyên khoa, giảm béo | `giambeo` |
| **KDC** | **Nha khoa / Răng hàm mặt** | Chuyên khoa RHM | `nhakhoa` |
| **KI** | **Kangnam Quốc tế** | Site `/en/`, khách nước ngoài & Việt kiều | *(dùng chung bộ dịch vụ, nhân bản song ngữ)* |
| **THV** | **Tiêu hoá Việt** | Thương hiệu trong nhóm, ngoài phạm vi thẩm mỹ | *(chưa có checklist chi tiết)* |

**Chuyên khoa / trung tâm:** Thẩm mỹ khuôn mặt · Tạo hình vóc dáng · Răng hàm mặt · Trung tâm điều trị & trẻ hoá da (Kangnam Beauty & Spa) · Giảm mỡ đa chuyên khoa (Kangnam Weightloss) · Chăm sóc sức khoẻ chủ động & quản trị lão hoá (Kangnam Wellness).

---

# 4. HỆ THỐNG CƠ SỞ — DỮ LIỆU LOCAL CHO GEO

**3 Bệnh viện thẩm mỹ + 7 Viện thẩm mỹ toàn quốc.**

> 🔧 **Đối chiếu `/chi-nhanh/` ngày 2026-10-16 — LỆCH, phải xác minh trước khi dùng cho local.**
> Trang chi nhánh chính thức hiện công bố **7 cơ sở tại 7 tỉnh thành: 2 bệnh viện thẩm mỹ** (Hà Nội 190 Trường Chinh — GP **194/BYT-GPHĐ**; Sài Gòn 666 CM Tháng 8 — GP **287/BYT-GPHĐ**) **+ 5 viện thẩm mỹ** (Hải Phòng · Nghệ An · Đà Nẵng · Cần Thơ · Thanh Hóa).
> **Ba cơ sở trong bảng dưới KHÔNG xuất hiện trên trang đó:** `BVTM Kangnam CS2 – 218 Nguyễn Trãi` · `Viện Trẻ hoá & Điều trị da công nghệ cao – 194 Trường Chinh` · `Chi nhánh Bình Dương`.
> Chưa đủ căn cứ để khẳng định ba cơ sở này đã đóng — có thể là pháp nhân khác hoặc trang chưa cập nhật. Nhưng **GEO/local nói về địa điểm**, nên nêu sai một cơ sở là chạm rào **R3 (đúng pháp nhân)**.
> → **Luật tạm thời: chỉ dùng 7 cơ sở có trên `/chi-nhanh/` cho nội dung local.** Ba cơ sở còn lại chỉ dùng sau khi Pháp chế xác nhận còn hoạt động và còn giấy phép.
> Chụp lại bất cứ lúc nào: `python ../Agent-LDP-Kangnam/tools/fetch-du-lieu.py --chi co_so`


| Vùng | Cơ sở | Địa chỉ |
|---|---|---|
| Sài Gòn | BVTM Kangnam Sài Gòn (CS1) | 666 Cách Mạng Tháng 8 |
| Sài Gòn | BVTM Kangnam (CS2) | 218 Nguyễn Trãi ⚠️ *không có trên /chi-nhanh/ 16/10/2026* |
| Hà Nội | BVTM Kangnam Hà Nội | 190 Trường Chinh |
| Hà Nội | Viện Trẻ hoá & Điều trị da công nghệ cao | 194 Trường Chinh ⚠️ *không có trên /chi-nhanh/ 16/10/2026* |
| Đà Nẵng | Chi nhánh Đà Nẵng | 293 Hùng Vương, Thanh Khê |
| Thanh Hoá | Chi nhánh Thanh Hoá | 103 Nguyễn Trãi, P. Hạc Thành |
| Hải Phòng | Chi nhánh Hải Phòng | 378 Tô Hiệu, Lê Chân |
| Nghệ An | Chi nhánh Nghệ An | 148 Nguyễn Văn Cừ, TP. Vinh |
| Cần Thơ | Chi nhánh Cần Thơ | 28 Lý Tự Trọng, Ninh Kiều |
| Bình Dương | Chi nhánh Bình Dương | 8D9 KDC Chánh Nghĩa, TP. Thủ Dầu Một ⚠️ *không có trên /chi-nhanh/ 16/10/2026* |

**8 hub chính đưa vào kế hoạch quý:** Hà Nội · TP.HCM · Hải Phòng · Nghệ An · Đà Nẵng · Cần Thơ · Bình Dương · Thanh Hoá.
**19 trang tỉnh vệ tinh:** KHÔNG nằm trong phạm vi quý — đẩy backlog.

**Vì sao local quan trọng với GEO:** trang chi nhánh chiếm **>1/3 traffic AI** vào landing page (≈1.008 phiên / 17 trang). Mẫu truy vấn *"địa chỉ [dịch vụ] ở [tỉnh]"* đã tự kéo traffic ở Cần Thơ, Vinh, Bình Dương dù chỉ là bài hỏi đáp ngắn. Mỗi trang chi nhánh phải chuẩn **NAP** (Name–Address–Phone) + nêu đúng **phạm vi giấy phép từng cơ sở** (viện tỉnh = tư vấn + tái khám; đại phẫu điều hướng về bệnh viện).

---

# 5. BÁC SĨ — TRẠNG THÁI XÁC MINH

**Nguyên tắc tuyệt đối:** chỉ gắn tên bác sĩ vào một dịch vụ khi bác sĩ đó **đã được xác minh chuyên khoa** VÀ **đã đăng ký hành nghề tại đúng cơ sở**. Vi phạm điều này là rào pháp lý **R4**.

| Trạng thái | Nội dung |
|---|---|
| Đã dùng trong tài liệu nội bộ | Dr. Richard Huy — thành viên hội chẩn 3 lớp (Bác sĩ phẫu thuật – Gây mê – Ekip & Dr. Richard Huy) |
| ⚠ **Xuất hiện trong traffic AI nhưng CHƯA xác minh chuyên khoa** | Mark Nguyễn · Galvin · Henry · Harvey — ~25 hồ sơ bác sĩ nhận gần **190 phiên AI**, nhiều hồ sơ top chưa xác minh. **Không gắn vào dịch vụ cho đến khi xác minh.** |
| ⚠ Danh sách đầy đủ đội ngũ | `Cần xác minh từ Kangnam` |

**Cơ hội GEO lớn nhất chưa khai thác:** ~25 hồ sơ bác sĩ đang hút gần 190 phiên AI mà chưa có schema `ProfilePage` / `IndividualPhysician` + `sameAs`. Xác minh → gắn bác sĩ vào dịch vụ → chiếm truy vấn *"bác sĩ [dịch vụ] giỏi"*. Đây là cụm **C14 — Thực thể thương hiệu & bác sĩ**, thuộc Tầng A ở hầu hết 17 bộ.

---

# 6. USP THEO DỊCH VỤ (dùng làm "bằng chứng" trong nội dung)

| Dịch vụ | USP đã có tài liệu |
|---|---|
| **Nâng mũi** | BS chuyên khoa mũi >13 năm KN · 120.000+ ca · 10.000+ ca mũi hỏng/khó · công nghệ Nâng mũi Idol độc quyền Hàn + AI Face Design · phòng mổ vô khuẩn cấp I |
| **Cắt mí** | Chuyên khoa thẩm mỹ mắt chuẩn Hàn · phân tích cấu trúc mí – tỉ lệ khuôn mặt – độ đàn hồi da |
| **Nâng ngực** | Chuyên khoa tạo hình vóc dáng chuẩn Hàn, BS >10 năm KN · thiết kế cân đối khung xương |
| **Giảm mỡ** | Công nghệ Lipo Tia Sương (Vaser + RF + Cold Air) · thiết kế dáng 360° |
| **Hàm mặt** | Chuyên khoa RHM chuyên sâu đầu tiên tại VN · AI Face Design + CT Scanner + mô phỏng 3D khớp cắn · hội chẩn 3 lớp |

**4 trụ cột chuẩn mực:** ① Bác sĩ đúng chuyên khoa trực tiếp khám–tư vấn–thực hiện · ② Công nghệ chuẩn Hàn nguồn gốc rõ ràng · ③ Quy trình khép kín + hội chẩn 3 lớp · ④ Y đức: minh bạch rủi ro.

⚠ Các cụm từ **"bảo hành trọn đời"**, **"cam kết không co thắt bao xơ"**, **"không tái mỡ"** xuất hiện trong tài liệu marketing cũ nhưng **VI PHẠM rào R1** (cam kết kết quả). Khi lập kế hoạch GEO, thay bằng *"chế độ theo dõi và chỉnh sửa theo chính sách"* và ghi chú cần Pháp chế duyệt.

---

# 7. TONE OF VOICE

**Brand Voice:** Chuyên môn – Điềm tĩnh – Trách nhiệm. Nói đúng, có căn cứ, không phô trương, không giật gân.

**Luôn:** chuyên gia · tận tâm · dễ hiểu · đáng tin cậy · có chiều sâu · hướng hành động.
**Không:** giật tít · gây sốc · khoa trương · đe doạ · hạ thấp đối thủ · ép mua · lạm dụng thuật ngữ y khoa.

**Từ ưu tiên:** an toàn · tự nhiên · đồng hành · chuyên môn · trải nghiệm · bác sĩ · công nghệ · phù hợp · tư vấn.
**Từ cấm (trừ khi có căn cứ + Pháp chế duyệt):** tuyệt đối · 100% · vĩnh viễn · hoàn hảo · không đau · không rủi ro · không biến chứng · rẻ nhất · tốt nhất · số 1.
**CTA nhẹ:** "Đăng ký tư vấn cùng bác sĩ" · "Đặt lịch thăm khám" · "Nhận phác đồ". Cấm: "Mua ngay / Chốt ngay / Kẻo hết".

---

# 8. HIỆN TRẠNG TRAFFIC AI (mốc nền — kỳ 01/01–11/09/2026)

Dùng làm **baseline** khi lập KPI. Nguồn: Data Studio "AI Search & LLM Traffic – kangnam" (GA4).

| Nguồn AI | Phiên | Tỷ trọng |
|---|---|---|
| ChatGPT | 1.857 | 87,1% |
| Gemini | 163 | 7,6% |
| Claude | 78 | 3,7% |
| Perplexity | 30 | 1,4% |
| Brave Search | 3 | 0,1% |
| **Tổng phiên AI** | **2.131** | — |
| Phiên từ nguồn khác (Google, direct, Facebook…) | 506.867 | — |
| **Tỷ trọng AI / tổng** | **0,42%** | — |

**Xu hướng theo tháng (tổng phiên AI):** T1 61 → T2 108 → T3 200 → T4 224 → T5 281 → T6 253 → T7 354 → T8 485 → T9 (đến 11/9) 162. **Tăng ~8 lần trong 8 tháng.**

**Landing page hút traffic AI theo loại trang:**

| Loại trang | Phiên AI | Tỷ trọng | Số trang |
|---|---|---|---|
| Chi nhánh | 1.008 | 37,8% | 17 |
| Trang chủ | 582 | 21,8% | 1 |
| Bác sĩ | 185 | 6,9% | 19 |
| Bảng giá | 107 | 4,0% | 2 |
| Dịch vụ theo tỉnh | 107 | 4,0% | 26 |
| Hỏi đáp – Giá | 102 | 3,8% | 32 |
| Kiến thức – Giá | 84 | 3,1% | 17 |
| Chuyên khoa | 53 | 2,0% | 13 |
| Hỏi đáp – Địa chỉ/Chọn nơi | 49 | 1,8% | 22 |

**Đọc ra chiến lược:** khách hỏi AI chủ yếu về **ĐỊA ĐIỂM** (chi nhánh + dịch vụ theo tỉnh ≈ 42%) và **GIÁ** (bảng giá + hỏi đáp giá + kiến thức giá ≈ 11%). Đây là lý do C04 Local, C07 Chi phí, C08 Chọn cơ sở, C14 Thực thể luôn nằm Tầng A.

---

# 9. DỮ LIỆU CẦN CẬP NHẬT ĐỊNH KỲ

Danh mục kỹ thuật (DMKT) từng pháp nhân · Giấy phép hoạt động từng cơ sở · Đội ngũ bác sĩ đã xác minh chuyên khoa · Bảng giá min–max theo dịch vụ · Chính sách bảo hành/theo dõi · Case có văn bản đồng ý · Số liệu GA4 & traffic AI hằng tháng · Kết quả đo prompt GEO hằng tháng.

