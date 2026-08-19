# Hướng dẫn người tổ chức

Tài liệu này dành cho người tổ chức kiểm tra, không phải tài liệu hướng dẫn thao tác cho người tham gia.

## Preparation

- Bắt đầu từ `main` sạch, chứa đúng bộ tài liệu ban đầu.
- Phân người tham gia vào Bài thực hành 01 hoặc Bài thực hành 02.
- Chỉ tạo thay đổi trên `main` sau khi người tham gia đã hoàn tất việc push branch ở Task 5.
- Không tạo sẵn branch cá nhân, thay đổi bài làm hoặc conflict trước khi bắt đầu.

## Tạo conflict sau khi người tham gia push branch

Mục tiêu là để Git tạo conflict tự nhiên khi người tham gia đưa `main` vào branch riêng. Muốn bảo đảm có conflict, thay đổi trên `main` phải chồng lấp với chính phần văn bản mà người tham gia đã thay đổi trên branch của họ.

### Đối với Practice 01

1. Mở phần thay đổi của người tham gia trong [requirement.md](requirement.md).
2. Trên `main`, chỉnh sửa cùng dòng hoặc cùng đoạn thuộc phần **User Requirement** bằng một nội dung nghiệp vụ khác.
3. Commit và push thay đổi trên `main`.
4. Yêu cầu người tham gia cập nhật `main` vào branch riêng và hoàn tất conflict.

### Đối với Practice 02

1. Mở phần thay đổi của người tham gia trong [test-case.md](test-case.md).
2. Trên `main`, chỉnh sửa cùng dòng hoặc cùng đoạn của Test Case mà người tham gia vừa cập nhật bằng một nội dung kiểm thử khác.
3. Commit và push thay đổi trên `main`.
4. Yêu cầu người tham gia cập nhật `main` vào branch riêng và hoàn tất conflict.

Không sửa sẵn tài liệu trước Task 5. Việc quan sát phần người tham gia vừa sửa rồi thay đổi đúng vùng đó trên `main` giúp conflict phát sinh một cách có chủ đích nhưng tự nhiên.

## Expected Workflow

Clone → Branch → Checkout → Edit → Add → Commit → Push → Update main → Merge → Resolve Conflict → Add → Commit → Push

## Scoring

Tổng: **8 điểm**

| Hạng mục | Điểm |
| --- | ---: |
| Clone Repository | 1 |
| Create / Checkout Branch | 1 |
| Chỉnh sửa tài liệu | 1 |
| Add + Commit | 1 |
| Push Branch | 1 |
| Cập nhật main | 1 |
| Merge | 1 |
| Resolve Conflict + Commit + Push | 1 |

**PASS:** 6/8 điểm.

**FAILED:** dưới 6/8 điểm.

Người tham gia bị đánh giá **FAILED** nếu không hoàn thành một trong ba bước quan trọng: Clone, Commit hoặc Push.

## Reset sau mỗi lượt kiểm tra

1. Ghi lại commit `main` ban đầu trước khi bắt đầu lượt kiểm tra.
2. Đánh giá branch của người tham gia trước khi dọn dẹp.
3. Đưa `main` trở về commit ban đầu đã ghi lại và cập nhật remote để mọi người nhận cùng một trạng thái xuất phát.
4. Xóa các branch thực hành đã kết thúc theo chính sách lưu trữ của team.
5. Kiểm tra lại `main` sạch, không có conflict và bảy tệp Markdown gốc vẫn đầy đủ.
