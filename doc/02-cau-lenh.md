# 02 · CÂU LỆNH CPW

---

# 1. Công thức ra lệnh

```
Viết bài "[TIÊU ĐỀ / TRUY VẤN KHÁCH GÕ]" — cụm [MÃ] line [DỊCH VỤ], dạng [DẠNG BÀI].
[Brief đính kèm / dán bên dưới]
```

**Bốn thông tin bắt buộc:** truy vấn hoặc tiêu đề · mã cụm · dịch vụ · dạng bài.
Thiếu dạng bài → Agent tự chọn theo bản đồ nội dung và nói rõ đã chọn gì, vì sao.

---

# 2. Prompt mẫu theo tình huống

## 2.1 Viết một bài có brief

```
Viết bài "Sửa mũi hỏng lần 2, lần 3 có được không, có giới hạn số lần không?"
— cụm C11 line Mũi, dạng Bài tình huống.

[dán nội dung từ: python tools/get-brief.py mui C11]
```

## 2.2 Viết trang trụ của cụm

```
Viết TRANG CHUYÊN BIỆT cho cụm C11 line Mũi (sửa mũi hỏng & tái phẫu thuật).
Đây là trang trụ, phủ ≥6/8 góc hỏi, 3.250 từ.
```

## 2.3 Viết cả lô bài của một cụm

```
Cụm C06 line Mũi cần 9 bài. Đề xuất danh sách 9 tiêu đề bám truy vấn thật,
mỗi bài ghi rõ dạng bài · độ dài · góc hỏi chính · rào pháp lý.
Chưa viết nội dung, chỉ lập danh sách để tôi duyệt.
```

Duyệt xong thì:
```
Ok. Viết bài số 3 trong danh sách.
```

## 2.4 Viết trang local

```
Viết TRANG LOCAL cho "Nâng mũi tại Hải Phòng — Kangnam Hải Phòng".
Nêu đúng phạm vi giấy phép của cơ sở này, đại phẫu điều hướng về bệnh viện.
```

## 2.5 Viết FAQ ngắn hàng loạt

```
Viết 8 FAQ ngắn (600 từ mỗi bài) cho cụm C10 hậu phẫu line Mũi,
dùng nguyên văn truy vấn khách gõ làm H1.
```

## 2.6 Sửa bài theo phiếu chấm của CPWCheck

```
Đây là phiếu chấm của CPWCheck cho bài vừa nộp. Sửa đúng các mục bị trừ,
ghi rõ đã sửa gì ở đâu. Không viết lại phần đang đạt.

[dán phiếu chấm]
```

---

# 3. Prompt hỏi đáp (không viết bài)

| Mục đích | Prompt |
|---|---|
| Chọn dạng bài | `Cụm C07 chi phí line Ngực nên viết dạng bài gì, dài bao nhiêu?` |
| Hiểu nỗi sợ | `Khách S5 của dịch vụ hút mỡ đang lo gì? Bài hậu phẫu phải có khối gì?` |
| Kiểm tra câu chữ | `Câu này có vi phạm rào nào không: "Cam kết dáng mũi đẹp tự nhiên trọn đời"?` |
| Dàn ý nhanh | `Lập dàn ý H2 cho bài "Bắn laser trị nám có bị đậm hơn không" — cụm C06 Sắc tố.` |
| Viết lại đoạn | `Đoạn này chưa BLUF, viết lại: "Nhiều chị em thắc mắc rằng..."` |
| Schema | `Bài trang local Kangnam Đà Nẵng cần schema JSON-LD nào?` |

---

# 4. Prompt tinh chỉnh sau bản nháp

```
Giữ nguyên bài, chỉ thêm một H2 về "ai không phù hợp" — đang thiếu góc
Trường hợp áp dụng (24,6% truy vấn).
```

```
Khối rủi ro đang ở cuối bài, chuyển lên giữa bài sau mục quy trình.
```

```
Bài đang 2.100 từ nhưng dạng Trang chuyên biệt chuẩn 3.250. Bổ sung phần nào?
Nêu đề xuất trước, đừng viết luôn.
```

```
Rút gọn còn 1.650 từ theo chuẩn Trang con, giữ nguyên khối rủi ro và bảng giá.
```

> Agent chỉ nêu phần thay đổi, không in lại toàn bộ bài trừ khi bạn yêu cầu.

---

# 5. Những gì Agent sẽ TỪ CHỐI hoặc CẢNH BÁO

| Yêu cầu | Phản hồi của Agent |
|---|---|
| "Mở bài giới thiệu Kangnam hàng đầu" | Từ chối; nêu phép thử cắt thương hiệu; đề xuất mở bằng tình huống khách |
| "Ghi cam kết không biến chứng" | Từ chối (**R1**); đề xuất *"chế độ theo dõi và chỉnh sửa theo chính sách"* |
| "Thêm tên bác sĩ X cho uy tín" | Kiểm tra trạng thái xác minh; chưa xác minh → `⚠ Cần xác minh chuyên khoa (KF-02)` (**R4**) |
| "So sánh với [tên đối thủ]" | Từ chối nêu tên (**R6**); đề xuất bộ tiêu chí khách quan |
| "Thêm case khách + ảnh before-after" | Hỏi đã có **văn bản đồng ý minh thị** chưa (**R5**); chưa có → không đưa vào |
| "Bịa tỷ lệ biến chứng cho thuyết phục" | Từ chối; ghi `⚠ Cần xác minh từ Kangnam` tại đúng vị trí |
| "Nhét từ khoá vào cho lên top" | Cảnh báo nhồi từ khoá cho kết quả **thấp hơn mức nền** trong AI search |
| "Bỏ phần rủi ro cho bài tích cực hơn" | Cảnh báo mất C2 (5đ) + trừ 5đ nhóm F, và mất đúng lợi thế đối thủ đang né |
