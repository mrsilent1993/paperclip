---
name: kiem-duyet-noi-dung
description: Checklist kiểm chứng sự thật, vùng cấm, chính sách YouTube và chất lượng kịch bản, kèm định dạng kết luận ĐẠT / SỬA / LOẠI.
---

# Kiểm duyệt nội dung

## Checklist

### A. Sự thật
- [ ] Mỗi khẳng định có số liệu đều có `[NGUỒN: research#n]`, và dòng đó tồn tại trong bảng sự thật.
- [ ] Số liệu trong kịch bản khớp với nguồn (đơn vị, bậc độ lớn, năm).
- [ ] Suy đoán được nói như suy đoán, không trình bày như sự thật.
- [ ] Không có "sự thật" phổ biến nhưng sai (ví dụ: "con người chỉ dùng 10% não").

### B. Vùng cấm và nhạy cảm
- [ ] Không chạm vùng cấm trong skill `chon-chu-de-what-if`.
- [ ] Không xúc phạm quốc gia, dân tộc, tôn giáo, giới tính.
- [ ] Không có hướng dẫn nguy hiểm có thể làm theo.

### C. Chính sách YouTube
- [ ] **Nguyên bản:** có lập luận và cú ngược riêng, không viết theo khuôn lặp lại so với các video trước của kênh (so tiêu đề và cấu trúc với 5 video gần nhất).
- [ ] **Thông tin sai lệch:** không đưa nội dung trái đồng thuận khoa học về sức khỏe, khí hậu, bầu cử.
- [ ] **Thân thiện quảng cáo:** không chửi thề, không mô tả bạo lực chi tiết, không hình ảnh gây sốc.
- [ ] **Công bố AI:** ghi chú nếu video sẽ dùng hình ảnh AI trông như thật về người hoặc sự kiện có thật.

### D. Chất lượng
- [ ] Tiếng Anh tự nhiên như người bản xứ nói: không dịch máy, không câu cứng, không sáo rỗng ("Little did they know…").
- [ ] Nhân vật hư cấu không được gán lời nói bịa đặt cho người có thật; nhân vật lịch sử chỉ "nói" những gì có nguồn.
- [ ] Cú ngược xuất hiện trong 30 giây đầu.
- [ ] Có vòng tò mò mới mỗi 60–90 giây.
- [ ] Kết thúc bằng câu hỏi tranh luận có hai phe.
- [ ] Tổng 1.200–2.200 từ.

## Định dạng tài liệu `review`

```markdown
# Kiểm duyệt Video #NN · Vòng 1
**Kết luận: ĐẠT | SỬA | LOẠI**

| # | Mục | Vị trí | Vấn đề | Đề xuất sửa | Mức độ (chặn/nên sửa) |
|---|---|---|---|---|---|

Ghi chú công bố AI: cần / không cần, vì …
```

- **ĐẠT:** không còn mục ở mức "chặn".
- **SỬA:** có ít nhất một mục "chặn" sửa được.
- **LOẠI:** vi phạm vùng cấm, hoặc cú ngược không đứng vững khi đối chiếu nguồn.
