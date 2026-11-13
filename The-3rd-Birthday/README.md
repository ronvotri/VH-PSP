# The 3rd Birthday — Việt hóa PSP

Dữ liệu gốc do người dùng cung cấp: `strings_to_translate.csv`, tổng 5.599 mục.

## Checkpoint 06 — 14/11/2026

| Đợt | Số mục | Trạng thái |
| --- | ---: | --- |
| 01 | 207 | CSV đã gửi trong chat; chưa nhập GitHub |
| 02 | 283 | `patch_02_268-597.psv` |
| 03 | 121 | `patch_03_598-750.psv` |
| 04 | 120 | `patch_04_1468-1653.psv` |
| 05 | 180 | `patch_05_2784-2977.psv` |
| 06 | 121 | `patch_06_3980-4100.psv` |
| **Tổng cộng từng đợt** | **1.032** | 1.032 ID duy nhất qua 6 đợt |

**Đã xác minh trong repository: 825 ID khác nhau từ đợt 02–06, không xung đột ID.** Kiểm tra CSV đợt 01: đúng 207 dòng tiếng Việt, ID trong khoảng 5–267, không trùng các ID đợt 02–05. **Tổng 1.032 ID dịch khác nhau (18,4% của 5.599).**

Bản hợp nhất mới: `translations_merged_02-06.psv` — 825 bản dịch.
Bản này **không phải** CSV gốc 5.599 hàng. Các tên nhân vật / model vũ khí chỉ có tính chất mã định danh không được tính là hoàn thành nếu chưa có dữ liệu dịch.

## Nguyên tắc

- PSV dạng `ID|Tiếng Việt`; bản gốc CSV 5 cột: `ID, Tiếng Anh, Tiếng Việt, Độ dài gốc, Ghi chú`.
- Khi áp dụng bản dịch phải ghép **theo ID**, không theo dòng hay khoảng ID.
- Giữ nguyên các chuỗi mã trong dấu ngoặc nhọn như `{fd20}`, `{191}`, `{1a5}` và ký hiệu xuống dòng `\\n`.
- Giữ nguyên tên riêng Aya Brea, Hyde, Gabrielle, Kyle, Overdive, Over Energy, Crossfire, Liberation, Twisted, Babel, CTI.
- Các nhãn hiệu, tên vũ khí và kỹ năng có thể giữ tiếng Anh cho nhất quán; dịch ý nghĩa phần mô tả.
- Chuỗi `(to be deleted)` được đánh dấu "dự kiến bỏ" và không coi là nội dung hội thoại đã xác minh.
- Chưa kiểm thử font, độ rộng hiển thị và độ dài chuỗi trên bản PSP.

## Việc còn thiếu

1. Đưa đủ 207 bản dịch đợt 01 vào repo để có bản hợp nhất chính thức.
2. Xuất CSV đầy đủ 5.599 mục cùng cả hai cột tiếng Anh/Việt.
3. Dịch tiếp nội dung chưa có tiếng Việt, ưu tiên lời thoại và ghi chú cốt truyện.
4. Chạy QA mã kỹ thuật, ngắt dòng, độ dài và kiểm thử hiển thị PSP.
