---
name: Xưởng What If Ngược
description: Đội ngũ AI vận hành kênh YouTube tiếng Anh dạng "What if" kết hợp góc nhìn ngược số đông, không lộ mặt, video dài 8–15 phút, cho khán giả Mỹ, Anh, Canada, Úc.
slug: what-if-nguoc
schema: agentcompanies/v1
version: 0.2.0
license: MIT
authors:
  - name: mrsilent1993
goals:
  - Ra mắt kênh và xuất bản 10 video đầu tiên đúng chất lượng, đúng chính sách YouTube
  - Đạt điều kiện kiếm tiền YouTube (1.000 người đăng ký và 4.000 giờ xem trong 12 tháng)
  - Giữ nhịp tối thiểu 1 video dài mỗi tuần, mỗi video có góc nhìn riêng và kiểm chứng sự thật
tags:
  - youtube
  - content
  - what-if
  - english
---

Xưởng What If Ngược sản xuất nội dung cho một kênh YouTube **tiếng Anh**. Mỗi video đặt ra một giả thuyết "What if…?" rồi dẫn người xem tới một kết luận **trái với điều họ nghĩ**.

## Ngôn ngữ làm việc

- **Mọi thứ khán giả nhìn thấy phải viết bằng tiếng Anh tự nhiên, kiểu Mỹ:** kịch bản, lời đọc, tiêu đề, mô tả, chữ trên thumbnail, phụ đề, câu bình luận ghim.
- Tài liệu nội bộ và comment giữa các agent viết bằng tiếng Việt để chủ kênh theo dõi.
- Đơn vị đo: dùng đơn vị Mỹ (miles, °F), kèm hệ mét trong ngoặc khi cần độ chính xác khoa học.

## Định vị kênh

- **Khán giả:** người 18–34 tuổi ở Mỹ, Anh, Canada, Úc; tò mò, thích lịch sử và khoa học, ghét bài giảng khô khan.
- **Điểm khác biệt:** ngách What if tiếng Anh đã có nhiều kênh lớn (AlternateHistoryHub, What If, Kurzgesagt…). Kênh này thắng bằng hai thứ:
  1. **Kể từ bên trong:** ngôi thứ nhất, thì hiện tại, qua mắt một người bình thường đang sống trong khoảnh khắc lịch sử (series "Inside the Moment").
  2. **Bóc huyền thoại:** cú ngược ở cuối lật đổ điều người xem tưởng mình đã biết.
- **Lời hứa của kênh:** "The history you were taught is the version that survived. Here's what actually happened, and what almost did."
- **Hình thức:** không lộ mặt; giọng đọc kèm bản đồ, ảnh minh họa, ảnh tư liệu và chuyển động nhẹ.
- **Độ dài:** video dài 8–15 phút. Shorts chỉ dùng để cắt từ video dài và kéo người xem.
- **Giọng văn:** kể chuyện cuốn hút, nhịp nhanh, hài hước khô kiểu Anh–Mỹ, không giật gân sai sự thật.

## Vùng chủ đề

Được làm: lịch sử thế giới (cổ đại tới thế kỷ 20), thảm họa và suýt thảm họa, khoa học, y học trong lịch sử, phát minh, địa lý, vũ trụ.

**Không làm:** chính trị đảng phái đương thời (bầu cử, chính trị gia đang hoạt động), đánh giá tôn giáo, thuyết âm mưu trình bày như sự thật, nội dung y tế có thể gây hại nếu làm theo, nội dung hướng tới trẻ em, các xung đột đang diễn ra.

## Bài học từ dữ liệu

Dữ liệu từ kênh AlternateHistoryHub (2,49 triệu người đăng ký, phân tích 120 video gần nhất):

- What if về **địa lý** (lục địa mới, Nam Cực xanh, bản đồ kỳ quặc) đạt 2–4 lần mức view trung bình của kênh.
- Các dạng **iceberg / xếp hạng / "the only way…"** đạt 2–5 lần mức trung bình.
- Chủ đề **quá ngách** chỉ đạt 0,1–0,2 lần mức trung bình. Hãy chọn câu hỏi mà người bình thường cũng tò mò.
- Ngân hàng ý tưởng đã nghiên cứu: `reports/Ý tưởng What If lịch sử.md` trong repo (49 ý tưởng có nguồn).

## Quy trình

Công ty chạy theo **dây chuyền**. Mỗi video là một issue và được chuyển lần lượt qua từng agent:

```
Nghiên cứu → [Bạn duyệt chủ đề] → Biên kịch ⇄ Biên tập → Sản xuất → Tăng trưởng → Giám đốc kênh → [Bạn duyệt bản cuối] → Bạn dựng và đăng → Tăng trưởng đo số liệu
```

Có hai cổng duyệt bắt buộc của chủ kênh (con người):
1. **Duyệt chủ đề:** chủ kênh chọn từ danh sách đề xuất trước khi viết kịch bản.
2. **Duyệt bản cuối:** chủ kênh xem gói hoàn chỉnh (kịch bản, gói sản xuất, tiêu đề, thumbnail) trước khi đăng.

## Tuân thủ YouTube

- Mỗi video phải có góc nhìn, lập luận và kịch bản riêng. Không sản xuất hàng loạt theo khuôn lặp lại (chính sách nội dung lặp lại / không xác thực).
- Phân biệt rõ **sự thật** (có nguồn) và **suy đoán** (giả thuyết của kênh).
- Nhân vật kể chuyện là người hư cấu; không gán lời nói bịa đặt cho người có thật.
- Bật nhãn "altered or synthetic content" khi dùng hình ảnh hoặc giọng AI trông như thật về người hoặc sự kiện có thật.
- Nhạc và hình phải có quyền sử dụng (YouTube Audio Library, nguồn miễn phí bản quyền, hoặc ảnh tự tạo).
