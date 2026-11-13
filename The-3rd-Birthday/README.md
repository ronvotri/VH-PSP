# The 3rd Birthday — Việt hóa PSP

## Checkpoint 13 — 14/11/2026

Dữ liệu nguồn: 5.599 hàng trong `strings_to_translate.csv`.

| Đợt | Số ID | Tệp |
|---|---:|---|
| 01 | 207 | CSV trong chat (chưa lên repo) |
| 02 | 283 | `patch_02_268-597.psv` |
| 03 | 121 | `patch_03_598-750.psv` |
| 04 | 120 | `patch_04_1468-1653.psv` |
| 05 | 180 | `patch_05_2784-2977.psv` |
| 06 | 121 | `patch_06_3980-4100.psv` |
| 07 | 149 | `patch_07_4101-4250.psv` |
| 08 | 100 | `patch_08_4251-4350.psv` |
| 09 | 128 | `patch_09_4351-4480.psv` |
| 10 | 106 | `patch_10_4481-4587.psv` |
| 11 | 90 | `patch_11_4588-4679.psv` |
| 12 | 95 | `patch_12_4680-4780.psv` |
| 13 | 111 | `patch_13_4781-4900.psv` |

- **Đã hợp nhất lên GitHub:** `translations_merged_02-13.psv` — **1.604 ID duy nhất**, không trùng giữa đợt 02–13.
- **Tổng tính cả đợt 01:** **1.811/5.599 (32,3%)**, chưa tính là QA hoàn chỉnh trong game.
- CSV đợt 01 gồm 207 bản dịch ID 5–267 hiện vẫn chưa được nhập vào GitHub.
- Chưa có một CSV hoàn chỉnh 5.599 hàng chứa đồng thời toàn bộ patch 01–10.
- Batch 12 đã đối chiếu thẻ mã và số \`\\n\` 95/95; batch 11 kiểm tra tự động 90/90 thẻ kỹ thuật và ký hiệu xuống dòng với nguồn; batch 10 đã QA số lần ký hiệu xuống dòng `\\n` và mọi thẻ định dạng với nguồn gốc: 106/106 đạt.
- Các patch trước đó và giới hạn hiển thị font PSP cần QA riêng.

## Nguyên tắc

Patch `.psv` gồm `ID|Tiếng Việt`. Khi nhập vào nguồn phải nối bằng ID và giữ nguyên các cột `Tiếng Anh`, `Độ dài gốc`, `Ghi chú`. Không thay đổi mã `{fd20}`, `{fe50}`, `{1a5}`, v.v. Không tính tên riêng giữ nguyên là dịch mới. Giữ cách gọi Aya, Eve, Hyde và các thuật ngữ Twisted, Babel, Overdive, Over Energy, Crossfire, Liberation.

## Việc còn lại

1. Đưa CSV đợt 01 và CSV nguồn 5.599 hàng vào repository.
2. Tạo bản nguồn hợp nhất thực sự, kiểm tra trùng ID và giữ nguyên mã game.
3. Dịch tiếp các ID chưa được xử lý; rà cách xưng hô và ngữ cảnh nhân vật.
4. Thử font, ngắt dòng và độ dài chuỗi trên PPSSPP/PSP.


## Checkpoint 13 — CSV tổng hợp chính thức (14/11/2026)

- `patch_13_4781-4900.psv`: **111 mục mới**.
- `translations_merged_02-13.psv`: **1.604 ID** trên GitHub từ đợt 02–13.
- `strings_translated_checkpoint_13.csv`: **5.599 hàng nguồn, 1.811 ID có bản Việt**, gồm cả 207 mục đợt 01; đây là CSV hợp nhất dùng để QA và nhập công cụ dựng game.
- `QA_checkpoint_13.md`: báo cáo **40 ID có số \\n khác nguồn**, **0 ID lệch thẻ {…}**, chưa được sửa tự động và cần rà trước khi nhập game.
- Đối chiếu phát hiện 4 ID có 2 phương án dịch ở đợt 12: 4698, 4719, 4735, 4739; ưu tiên bản mới trên GitHub.

**Tiến độ dịch: 1.811 / 5.599 (32,3%).** Chưa xác nhận font PSP và giới hạn số ký tự hiển thị.

> Các mô tả checkpoint 11/12 trước đây nói thiếu bản tổng. Kể từ checkpoint 13, **bản CSV đầy đủ đã có trên GitHub**; xem liên kết mới ở trên.


## Checkpoint 14 — 14/11/2026

- Batch 14: `patch_14_4901-5040.psv` — 137 new dialogue translations.
- Full source CSV: `strings_translated_checkpoint_14.csv` — 5,599 source rows; **1,948 translated IDs (34.8%)**, including batch 01–14.
- Merged patch 02–14: `translations_merged_02-14.psv` — **1,741 unique IDs**.
- QA batch 14: 137/137 code tags and `\n` escape counts match source.
- `QA_checkpoint_14.md` documents **40 inherited newline-count discrepancies** (27 missing one, 13 extra one); do not automatically rewrite lines before contextual review.
- In-game rendering on PSP/PPSSPP has not been tested.
