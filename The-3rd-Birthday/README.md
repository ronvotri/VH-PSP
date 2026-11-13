# The 3rd Birthday — Việt hóa PSP

## Checkpoint 12 — 14/11/2026

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

- **Đã hợp nhất lên GitHub:** `translations_merged_02-12.psv` — **1.493 ID duy nhất**, không trùng giữa đợt 02–12.
- **Tổng tính cả đợt 01:** **1.700/5.599 (30,4%)**, chưa tính là QA hoàn chỉnh trong game.
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
