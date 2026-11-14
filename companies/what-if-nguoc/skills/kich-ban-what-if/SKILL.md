---
name: kich-ban-what-if
description: Cấu trúc, giọng văn và định dạng kịch bản lời đọc tiếng Anh 8–15 phút cho video "What if" với góc nhìn ngược, gồm dạng giải thích và dạng kể chuyện ngôi thứ nhất "Inside the Moment".
---

# Kịch bản What if

**Kịch bản viết bằng tiếng Anh Mỹ tự nhiên**, như một người kể chuyện giỏi nói, không như văn viết học thuật. Ghi chú cho đội (nếu có) viết tiếng Việt trong ngoặc vuông.

## Hai dạng video

1. **Explainer:** người dẫn chuyện nói với người xem ("you"), dùng cho What if khoa học/địa lý.
2. **Inside the Moment:** ngôi thứ nhất, thì hiện tại, qua mắt một người bình thường hư cấu sống trong khoảnh khắc lịch sử. Xen kẽ với giọng người dẫn chuyện ở phần bối cảnh và cú ngược.

## Cấu trúc bắt buộc

| Phần | Thời lượng | Mục tiêu |
|---|---|---|
| 1. **Cold open** | 0:00–0:30 | Explainer: nêu câu hỏi, nói điều người xem tin, rồi lật ngay ("You were taught X. That's not what happened."). Inside the Moment: thả người xem vào giữa cảnh, có âm thanh, mùi, cảm giác cơ thể. |
| 2. **Bối cảnh** | 0:30–2:00 | Vì sao điều này không xảy ra ngoài đời, hoặc thế giới lúc đó ra sao. Kiến thức nền tối thiểu, bằng ví dụ đời thường. |
| 3. **Diễn biến theo mốc thời gian** | 2:00–(cuối − 2:30) | Mỗi mốc mở bằng một câu gây tò mò, kết bằng hệ quả cụ thể. Với Inside the Moment: nhân vật chỉ biết những gì tin tức kịp đến tay họ. |
| 4. **Cú ngược thứ hai** | khoảng 2 phút | Hệ quả không ai ngờ, liên hệ về thế giới hôm nay. |
| 5. **Kết và câu hỏi tranh luận** | 30–45 giây | Tóm lại trong 1 câu; hình ảnh mở đầu quay lại với nghĩa mới; đặt một câu hỏi có hai phe rõ ràng để người xem bình luận. |

## Độ dài

- Tốc độ đọc tiếng Anh khoảng 150 từ/phút, nên video 8–15 phút cần **1.200–2.200 từ**.
- Câu ngắn, trung bình 10–16 từ. Mỗi đoạn tối đa 3 câu.

## Kỹ thuật giữ chân

- **Open loops:** cứ 60–90 giây mở một câu hỏi và giải ở đoạn sau ("But that wasn't the worst part.").
- **Con số cụ thể** thay cho tính từ ("1,000 miles an hour" thay vì "really fast").
- **So sánh đời thường** với đời sống Mỹ/Anh ("faster than a commercial jet").
- **Một chi tiết "gross but true"** có nguồn cho mỗi video lịch sử.
- Không chào hỏi dài, không xin subscribe trong 60 giây đầu.

## Giọng văn

- Cuốn hút, tò mò, hài hước khô. Tránh từ sáo rỗng ("Little did they know", "In a world where…").
- Sự thật thì nói chắc ("According to NASA…"); suy đoán thì nói rõ ("Most likely…", "If we assume…"); tranh luận học thuật thì nói rõ ("Historians still argue about this.").
- Nhân vật Inside the Moment không dùng từ ngữ hay suy nghĩ hiện đại; họ hiểu thế giới bằng niềm tin của thời đó.

## Định dạng tài liệu `script`

```markdown
# Video #NN: <working title>
Words: ~1,800 · Est. runtime: ~12 min · Format: Explainer | Inside the Moment

## 1. Cold open (0:00–0:30)
[VISUAL: Earth from orbit, suddenly lurching to a stop]
VO: You've probably heard that if the Earth stopped spinning, everything would just... stop. ...
[SOURCE: research#3]
```

- `[VISUAL: …]` là gợi ý cho Nhà sản xuất. Lời đọc chỉ nằm sau `VO:`.
- `[SOURCE: research#n]` trỏ tới dòng trong bảng sự thật, đặt sau mỗi khẳng định có số liệu.
