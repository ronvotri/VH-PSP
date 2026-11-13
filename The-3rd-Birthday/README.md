# The 3rd Birthday — Việt hóa PSP

Nguồn: `strings_to_translate.csv` do người dùng cung cấp, tổng 5.599 mục.

## Checkpoint 04 — 14/11/2026

| Đợt | Mục dịch | Trạng thái |
| --- | ---: | --- |
| 01 | 207 | CSV gửi trong chat; **chưa đưa lên GitHub** |
| 02 | 283 | `patch_02_268-597.psv` |
| 03 | 121 | `patch_03_598-750.psv` |
| 04 | 120 | `patch_04_1468-1653.psv` |
| **Tổng từng đợt** | **731** | **13,1% nếu 207 mục đợt 01 không trùng** |

- **Đã xác minh bằng dữ liệu trên GitHub:** 524 ID khác nhau, không trùng hoặc xung đột giữa đợt 02–04.
- **Bản hợp nhất GitHub:** `translations_merged_02-04.psv` (524 ID).
- Không nên hiểu bản hợp nhất này là CSV có đủ toàn bộ 5.599 hàng; file này chỉ chứa các ID đã dịch trong đợt 02–04.
- Đợt 01 vẫn cần đưa lên repo và đối chiếu trùng ID trước khi khẳng định tổng ID đã dịch thật sự là 731.

## Nguyên tắc

- `.psv` gồm hai cột `ID|Tiếng Việt`. Ghép vào CSV gốc **theo ID**, không theo thứ tự hàng.
- Giữ nguyên `{fd20}`, `{191}` và các mã kỹ thuật, cùng ký hiệu `\\n`.
- Không dịch tên người ngẫu nhiên chỉ để tăng số mục. Tên riêng được giữ nguyên.
- Ưu tiên hội thoại tự nhiên, giọng nhân vật nhất quán; giữ thuật ngữ Overdive, Liberation, Over Energy, Twisted, Babel.
- Mô tả và menu có thể còn phải tinh gọn sau thử nghiệm font, glyph và độ rộng hiển thị trên PSP.

## Các bước kế tiếp

1. Hợp nhất CSV đợt 01 vào bảng nguồn đầy đủ và kiểm tra số ID duy nhất.
2. Tạo CSV 5.599 hàng (cột tiếng Anh không thay đổi), áp dụng các bản dịch theo ID.
3. Dịch các mục chưa có tiếng Việt, đặc biệt hội thoại và mô tả kỹ năng.
4. Chạy QA bảo toàn mã điều khiển, ký hiệu xuống dòng, tên riêng và giới hạn giao diện.
