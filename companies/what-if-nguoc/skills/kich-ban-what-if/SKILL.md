---
name: kich-ban-what-if
description: Cấu trúc, giọng văn và định dạng kịch bản lời đọc 8–15 phút cho video "What if" với góc nhìn ngược, tối ưu giữ chân người xem.
---

# Kịch bản What if

## Cấu trúc bắt buộc

| Phần | Thời lượng | Mục tiêu |
|---|---|---|
| 1. **Mở đầu ngược** | 0:00–0:30 | Nêu câu hỏi, nói điều người xem đang nghĩ, rồi lật ngược ngay: "Bạn nghĩ X… thực ra là Y." Hứa hẹn điều sẽ được giải đáp ở cuối. |
| 2. **Bối cảnh** | 0:30–2:00 | Vì sao điều này không xảy ra ngoài đời. Đưa kiến thức nền tối thiểu, bằng ví dụ đời thường. |
| 3. **Diễn biến theo mốc thời gian** | 2:00–(cuối − 2:30) | 1 giây → 1 ngày → 1 năm → 100 năm (hoặc mốc phù hợp). Mỗi mốc mở bằng một câu gây tò mò, kết bằng hệ quả cụ thể. |
| 4. **Cú ngược thứ hai** | khoảng 2 phút | Hệ quả không ai ngờ, liên hệ ngược về đời sống người xem. |
| 5. **Kết và câu hỏi tranh luận** | 30–45 giây | Tóm lại trong 1 câu, đặt một câu hỏi có hai phe rõ ràng để người xem bình luận. Gợi ý video tiếp theo. |

## Độ dài

- Tốc độ đọc khoảng 150 từ/phút, nên video 8–15 phút cần **1.200–2.200 từ**.
- Câu ngắn, trung bình 12–18 từ. Mỗi đoạn tối đa 3 câu.

## Kỹ thuật giữ chân

- **Vòng tò mò:** cứ 60–90 giây mở một câu hỏi và giải ở đoạn sau ("Nhưng đó chưa phải điều tệ nhất…").
- **Con số cụ thể** thay cho tính từ ("1.600 km/h" thay vì "rất nhanh").
- **So sánh đời thường** ("nhanh hơn máy bay chở khách gấp đôi").
- **Gọi thẳng người xem:** "bạn", "nhà bạn", "chiếc điện thoại trên tay bạn".
- Không chào hỏi dài, không xin đăng ký trong 60 giây đầu.

## Giọng văn

- Thân mật, tò mò, hài hước nhẹ. Không giật gân sai sự thật, không hù dọa.
- Phân biệt rõ: sự thật thì nói chắc ("Theo NASA…"), suy đoán thì nói rõ là suy đoán ("Nhiều khả năng…", "Nếu giả định rằng…").

## Định dạng tài liệu `script`

```markdown
# Video #NN: <tiêu đề làm việc>
Số từ: ~1.800 · Thời lượng ước tính: ~12 phút

## 1. Mở đầu ngược (0:00–0:30)
[HÌNH: Trái Đất nhìn từ vũ trụ, đột ngột khựng lại]
Lời: Bạn nghĩ nếu Trái Đất ngừng quay, mọi thứ sẽ đứng yên? ...
[NGUỒN: research#3]
```

- `[HÌNH: …]` là gợi ý cho Nhà sản xuất. Lời đọc chỉ nằm sau `Lời:`.
- `[NGUỒN: research#n]` trỏ tới dòng trong bảng sự thật, đặt sau mỗi khẳng định có số liệu.
