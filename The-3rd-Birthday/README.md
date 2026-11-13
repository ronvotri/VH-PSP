# The 3rd Birthday — Việt hóa PSP

Nguồn: `strings_to_translate.csv` do người dùng cung cấp, 5.599 dòng dữ liệu.

## Tiến độ (14/11/2026)
- Đợt 01: 207 mục được dịch trong file `The_3rd_Birthday_Viet_Hoa_Dot_01.csv` (bản tải trong cuộc trò chuyện gốc; chưa được đưa vào repository).
- Đợt 02: 283 mục mới trong `patch_02_268-597.psv`, đã commit lên GitHub.
- **Tổng đã dịch qua hai đợt: 490 / 5.599 mục (khoảng 8,8%)**. Không tính các chuỗi mã nội bộ chưa dịch.
- **Lưu ý:** repository hiện mới chứa dữ liệu dịch đợt 02; chưa có bản CSV hợp nhất và chưa xác nhận giới hạn glyph/font trong bản PSP.

## Quy tắc dữ liệu
- File .psv là bảng ánh xạ `ID|Tiếng Việt`, ngắt dòng trong game viết nguyên văn là `\n` (hai ký tự dấu gạch chéo ngược và n).
- Áp dụng các cặp này lên CSV nguồn **theo ID**, không theo vị trí hàng.
- Luôn giữ cột tiếng Anh gốc và tất cả ID; không ghi đè bản dịch đã có khi chưa review.
- Các thẻ như `{fd20}`, `{19a}`, `{191}` và `{1a5}` phải giữ nguyên.
- Mã game `MSG_...`, ký hiệu test và tên riêng cần được kiểm tra trước khi dịch.
- Khuyến nghị QA: đối chiếu thẻ kỹ thuật, newline, thứ tự hàng, mã hóa tiếng Việt và độ dài giao diện.

## Hướng dịch
Câu thoại tự nhiên, nhất quán quan hệ nhân vật; bảo toàn Aya Brea, Hyde Bohr, CTI, Twisted, Babel, Overdive, Over Energy, Liberation, Overdive Kill. UI ưu tiên ngắn, rõ, có thể chỉnh khi thử trên phần cứng.

## Lần tiếp theo
1. Nhập bản CSV đợt 01 vào repo làm baseline đầy đủ.
2. Ghép patch đợt 02; kiểm đếm và tránh trùng ID.
3. Dịch tiếp từ các mục chưa có tiếng Việt, ưu tiên tăng kích thước đợt nhưng không bỏ QA.
