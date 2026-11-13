# The 3rd Birthday — Việt hóa PSP

Dữ liệu gốc do người dùng cung cấp: `strings_to_translate.csv`, tổng 5.599 mục.

## Checkpoint 05 — 14/11/2026

| Đợt | Số mục | Trạng thái |
| --- | ---: | --- |
| 01 | 207 | CSV đã gửi trong chat; chưa nhập GitHub |
| 02 | 283 | `patch_02_268-597.psv` |
| 03 | 121 | `patch_03_598-750.psv` |
| 04 | 120 | `patch_04_1468-1653.psv` |
| 05 | 180 | `patch_05_2784-2977.psv` |
| **Tổng cộng từng đợt** | **911** | Chưa xác thực trùng ID với đợt 01 |

**Đã xác minh trong repository: 704 ID khác nhau từ đợt 02–05, không xung đột ID.**

Bản hợp nhất mới: `translations_merged_02-05.psv` — 704 bản dịch.
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

1. Đưa đủ 207 bản dịch đợt 01 vào repo, rà trùng ID với 02–05.
2. Xuất CSV đầy đủ 5.599 mục cùng cả hai cột tiếng Anh/Việt.
3. Dịch tiếp nội dung chưa có tiếng Việt, ưu tiên lời thoại và ghi chú cốt truyện.
4. Chạy QA mã kỹ thuật, ngắt dòng, độ dài và kiểm thử hiển thị PSP.
