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
