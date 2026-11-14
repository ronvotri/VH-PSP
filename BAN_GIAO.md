# THE 3RD BIRTHDAY (PSP) — BÀN GIAO VIỆT HÓA

Ngày bàn giao: 14/11/2026 — Checkpoint 18.

## Tệp quan trọng nhất

**The_3rd_Birthday_Viet_Hoa_Checkpoint_18.csv**

- 5.599 hàng nguồn gốc, 5 cột: `ID`, `Tiếng Anh`, `Tiếng Việt`, `Độ dài gốc`, `Ghi chú`.
- **2.549 ID có bản Việt** (45,5%); còn 3.050 ID chưa được dịch.
- Đã hợp nhất các bản dịch đợt 01–18; **không phải chỉ danh sách ID chưa dịch**.
- Đọc/ghi bằng UTF-8, giữ nguyên ID, nhãn và các mã dạng `{fd22}`, `{fe4f}`, `{1a5}` và ký hiệu xuống dòng `\\n`.
- Để tiếp tục dịch, chỉ điền những ô trống của cột `Tiếng Việt`; không làm xáo trộn những cột khác.

## Tệp bổ trợ

- `Ban_dich_hop_nhat_02-18.psv`: 2.342 ID tiếng Việt từ patch 02–18, không bao gồm 207 ID đợt 01; toàn bộ 2.549 ID đã nằm trong CSV chính.
- `Patch_18_5331-5653.psv`: 320 ID bổ sung của đợt 18.
- `QA_Checkpoint_18.md`: báo cáo kỹ thuật, 40 mục có dấu xuống dòng khác nguồn trong các đợt trước và các bước kiểm thử còn thiếu.

## Tình trạng chất lượng

- Batch 18: 320/320 mục đạt đối chiếu mã kỹ thuật và số ký hiệu xuống dòng theo CSV nguồn.
- **40 cảnh báo xuống dòng từ các đợt trước chưa xử lý xong.** Có thể là điều chỉnh bố cục hợp lệ hoặc lỗi cần sửa; không coi là vượt QA.
- **Chưa chạy kiểm thử font và độ rộng dòng thực tế trên PSP/PPSSPP**. Chưa có bản ISO/ROM Việt hóa đóng gói.
- Kiểm tra lại ngôi xưng Aya, Eve, Gabrielle, Kyle, Hyde và thuật ngữ Twisted, Babel, Overdive, High Ones, Time Zero trước khi phát hành.

## Nguồn lưu tiến độ

Repo chính: https://github.com/ronvotri/VH-PSP/tree/main/The-3rd-Birthday

Bản này là **gói dữ liệu Việt hóa**, không chứa game gốc hoặc tệp chạy PSP.

## Đề nghị bàn giao cho người tiếp tục

1. Mở CSV chính; xác nhận 5.599 hàng và 2.549 ô tiếng Việt có nội dung.
2. Rà 40 cảnh báo trong báo cáo QA và kiểm tra hiển thị trên game.
3. Tiếp tục dịch 3.050 ID còn trống bằng tiếng Anh gốc, giữ nguyên mã điều khiển và cấu trúc.
4. Cập nhật checkpoint CSV, báo cáo QA và git commit cho mỗi đợt.
