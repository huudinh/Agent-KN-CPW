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
