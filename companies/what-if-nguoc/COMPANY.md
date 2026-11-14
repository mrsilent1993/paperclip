---
name: Xưởng What If Ngược
description: Đội ngũ AI vận hành kênh YouTube tiếng Việt dạng "What if" kết hợp góc nhìn ngược số đông, không lộ mặt, video dài 8–15 phút.
slug: what-if-nguoc
schema: agentcompanies/v1
version: 0.1.0
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
  - vietnamese
---

Xưởng What If Ngược sản xuất nội dung cho một kênh YouTube tiếng Việt. Mỗi video đặt ra một giả thuyết "Nếu… thì sao?" rồi dẫn người xem tới một kết luận **trái với điều họ nghĩ**.

## Định vị kênh

- **Khán giả:** người Việt 16–35 tuổi, tò mò, thích kiến thức nhưng ghét bài giảng khô khan.
- **Lời hứa của kênh:** "Mọi câu hỏi What if đều có một câu trả lời bạn không ngờ tới."
- **Hình thức:** không lộ mặt; giọng đọc (người thật hoặc AI) kèm bản đồ, ảnh minh họa, ảnh tư liệu và chuyển động nhẹ.
- **Độ dài:** video dài 8–15 phút. Shorts chỉ dùng để cắt từ video dài và kéo người xem.
- **Giọng văn:** thân mật, nhịp nhanh, hài hước nhẹ, không giật gân sai sự thật.

## Vùng chủ đề

Được làm: khoa học, vũ trụ, địa lý, sinh học, xã hội và kinh tế giả định, công nghệ, lịch sử thế giới cổ đại và trung đại.

**Không làm:** chính trị Việt Nam, lịch sử hiện đại Việt Nam (chiến tranh, chế độ, lãnh đạo), tôn giáo theo hướng đánh giá, chủ đề y tế có thể gây hại nếu làm theo, nội dung hướng tới trẻ em.

## Bài học từ dữ liệu

Dữ liệu từ kênh AlternateHistoryHub (2,49 triệu người đăng ký, phân tích 120 video gần nhất):

- What if về **địa lý** (lục địa mới, Nam Cực xanh, bản đồ kỳ quặc) đạt 2–4 lần mức view trung bình của kênh.
- Các dạng **iceberg / xếp hạng / "cách duy nhất để…"** đạt 2–5 lần mức trung bình.
- Chủ đề **quá ngách** chỉ đạt 0,1–0,2 lần mức trung bình. Hãy chọn câu hỏi mà người bình thường cũng tò mò.

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
- Bật nhãn "nội dung đã chỉnh sửa hoặc tổng hợp" khi dùng hình ảnh AI trông như thật.
- Nhạc và hình phải có quyền sử dụng (YouTube Audio Library, nguồn miễn phí bản quyền, hoặc ảnh tự tạo).
