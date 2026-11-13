# The 3rd Birthday — Việt hóa PSP

Dữ liệu gốc: `strings_to_translate.csv` (5.599 hàng dữ liệu, do người dùng cung cấp).

## Checkpoint 07 — 14/11/2026

| Đợt | ID đã dịch | Tệp |
| --- | ---: | --- |
| 01 | 207 | CSV đợt 01 trong cuộc trò chuyện; **chưa lưu lên repo** |
| 02 | 283 | `patch_02_268-597.psv` |
| 03 | 121 | `patch_03_598-750.psv` |
| 04 | 120 | `patch_04_1468-1653.psv` |
| 05 | 180 | `patch_05_2784-2977.psv` |
| 06 | 121 | `patch_06_3980-4100.psv` |
| 07 | 149 | `patch_07_4101-4250.psv` |

**Kiểm đếm theo ID: 974 bản dịch đã có trên GitHub (đợt 02–07); không xung đột ID.** Thêm 207 mục đợt 01 nằm trong CSV đã gửi ở chat (khoảng ID 5–267), tổng dự kiến **1.181 ID / 5.599 mục (~21,1%)**, với điều kiện nhập đợt 01 đúng nguyên trạng.

- Bản hợp nhất hiện có: `translations_merged_02-07.psv` (**974 ID**); bản này mới là patch bảng ánh xạ, **không phải CSV đầy đủ**.
- Cần nhập CSV đợt 01 lên GitHub và tạo CSV gốc 5.599 hàng có cả tiếng Anh và Việt. Chưa hoàn thành.
- Nội dung mới cần QA theo ngữ cảnh và kiểm tra độ rộng font trên máy PSP / PPSSPP.

## Quy tắc dịch

- Mỗi patch là `ID|Tiếng Việt`, ghép dựa trên ID chứ không dựa số thứ tự hoặc khoảng ID.
- Giữ nguyên mọi mã dạng `{fd20}`, `{fe5a}`, `{1a5}` và chuỗi `\\n`; một số câu bị chia giữa ID nên phải đối chiếu cảnh trong game trước khi ghép.
- Giữ các thuật ngữ Overdive, Over Energy, Liberation, Twisted, Babel, CTI, Crossfire, Overdive Kill.
- Không tự dịch các tên ngẫu nhiên chỉ để tăng số lượng.
- Không tự nhận đã qua QA in-game trước khi kiểm tra.

## Ưu tiên

1. Tạo bản CSV hợp nhất thực sự, có đủ 5.599 hàng và bản dịch đợt 01–07.
2. Kiểm tra tự động thẻ kỹ thuật và số dòng, đánh dấu lỗi QA.
3. Dịch hội thoại tiếp sau ID 4250, giữ ngữ cảnh và nhân xưng.
