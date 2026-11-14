# Xưởng What If Ngược

Đội ngũ 6 AI agent vận hành một kênh YouTube tiếng Việt dạng **"What if" kết hợp góc nhìn ngược**: mỗi video đặt một giả thuyết "Nếu… thì sao?" rồi dẫn người xem tới kết luận trái với điều họ nghĩ. Kênh không lộ mặt, video dài 8–15 phút.

## Cách công ty vận hành

Mỗi video là một issue, được chuyển qua dây chuyền:

```
Nhà nghiên cứu ──► [BẠN duyệt chủ đề] ──► Biên kịch ⇄ Biên tập ──► Nhà sản xuất
        ──► Tăng trưởng ──► Giám đốc kênh ──► [BẠN duyệt bản cuối]
        ──► BẠN tạo giọng, dựng, đăng ──► Tăng trưởng đo số liệu ──► bài học cho vòng sau
```

Mỗi khâu để lại một tài liệu trên issue: `research` → `script` → `review` → `production` → `packaging` → `final` → `metrics`.

**Phần việc của bạn (con người):** duyệt chủ đề, duyệt bản cuối, tạo giọng đọc và dựng video theo gói sản xuất (khoảng 2–4 giờ mỗi video với CapCut), tải lên YouTube, dán link và số liệu YouTube Studio vào issue.

## Sơ đồ tổ chức

| Agent | Vai trò | Báo cáo cho | Skill |
|---|---|---|---|
| **Giám đốc kênh** (`giam-doc-kenh`) | Điều phối dây chuyền, hai cổng duyệt với chủ kênh, báo cáo tuần | — | paperclip, chon-chu-de-what-if, dong-goi-video |
| **Nhà nghiên cứu** (`nghien-cuu`) | Đề xuất chủ đề, hồ sơ nghiên cứu, bảng sự thật có nguồn | Giám đốc kênh | paperclip, chon-chu-de-what-if |
| **Biên kịch** (`bien-kich`) | Viết kịch bản lời đọc 1.200–2.200 từ | Giám đốc kênh | paperclip, kich-ban-what-if |
| **Biên tập viên** (`bien-tap`) | Kiểm chứng sự thật, chính sách YouTube, vùng cấm; kết luận ĐẠT / SỬA / LOẠI | Giám đốc kênh | paperclip, kiem-duyet-noi-dung, kich-ban-what-if |
| **Nhà sản xuất** (`san-xuat`) | Lời đọc, bảng phân cảnh, prompt ảnh AI, nhạc, các bước dựng CapCut, Shorts | Giám đốc kênh | paperclip, goi-san-xuat |
| **Tăng trưởng** (`tang-truong`) | Tiêu đề, thumbnail, mô tả, SEO, theo dõi số liệu và rút bài học | Giám đốc kênh | paperclip, dong-goi-video |

## Skill riêng

| Skill | Nội dung |
|---|---|
| `chon-chu-de-what-if` | Rubric chấm 6 tiêu chí (tối đa 30 điểm), vùng cấm, bài học từ dữ liệu |
| `kich-ban-what-if` | Cấu trúc 5 phần, kỹ thuật giữ chân người xem, định dạng kịch bản |
| `kiem-duyet-noi-dung` | Checklist sự thật / nhạy cảm / chính sách YouTube / chất lượng |
| `goi-san-xuat` | Định dạng gói sản xuất, prompt ảnh AI đồng bộ, nguồn âm thanh hợp lệ |
| `dong-goi-video` | Công thức tiêu đề, thumbnail, mô tả, ngưỡng số liệu |

## Việc có sẵn

**Dự án "Ra mắt kênh":**
- Định vị và nhận diện kênh (Tăng trưởng)
- Lập lịch 10 video đầu tiên (Nhà nghiên cứu)
- Video #01: chạy thử trọn dây chuyền (Giám đốc kênh)

**Việc định kỳ** (giờ Việt Nam):
- Đề xuất chủ đề: thứ Hai 9:00 (Nhà nghiên cứu)
- Theo dõi số liệu: thứ Tư và thứ Bảy 10:00 (Tăng trưởng)
- Báo cáo tuần: Chủ nhật 20:00 (Giám đốc kênh)

## Bắt đầu

```sh
paperclipai company import --from ./companies/what-if-nguoc
```

Sau khi nhập, giao việc cho agent hoặc bật các việc định kỳ trong Paperclip. Gói không chỉ định adapter, nên Paperclip sẽ dùng adapter mặc định của bạn.

## Tham khảo

- [Đặc tả Agent Companies](https://agentcompanies.io/specification)
- [Paperclip](https://github.com/paperclipai/paperclip)
