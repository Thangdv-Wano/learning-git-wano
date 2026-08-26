# Test Case

## TC-001 — Xem danh sách tài liệu

### Preconditions

Người dùng đã đăng nhập vào hệ thống.

### Steps

1. Mở màn hình danh sách tài liệu.
2. Kiểm tra danh sách tài liệu.

### Expected Result

Danh sách tài liệu được hiển thị.

## Notes

Test Case được quản lý bằng Git để các thành viên có thể cùng cập nhật và theo dõi lịch sử thay đổi.

## TC-002 — Tạo mới và chỉnh sửa tài liệu dự án

### Preconditions

Người dùng đã đăng nhập hệ thống với quyền **Biên tập viên (Editor)** hoặc **Quản trị viên (Admin)**.

### Steps

1. Nhấp chọn **"Tạo tài liệu mới"** trên thanh công cụ.
2. Nhập đầy đủ thông tin bắt buộc: **Tiêu đề**, **Danh mục**, và **Nội dung chi tiết**.
3. Nhấn **"Lưu nháp"**, sau đó tiến hành chỉnh sửa nội dung và nhấn **"Xuất bản"**.

### Expected Result

- Tài liệu mới được tạo thành công và xuất hiện ngay trong danh sách tài liệu chung.
- Toàn bộ nội dung cập nhật được lưu chính xác, hệ thống ghi nhận đúng **Lịch sử phiên bản (Version History)**.

## Test Case — Tạo tài liệu mới


### Mục tiêu

Kiểm tra người dùng có thể tạo và mở lại một tài liệu mới thành công trên hệ thống.

### Điều kiện

Người dùng đã đăng nhập và đang ở màn hình quản lý tài liệu.

### Các bước thực hiện

1. Mở màn hình quản lý tài liệu.
2. Chọn chức năng tạo tài liệu mới.
3. Nhập đầy đủ thông tin cần thiết.
4. Chọn lưu tài liệu.

### Kết quả mong đợi

Tài liệu mới được tạo thành công và được hiển thị ngay trong danh sách tài liệu.

### Ghi chú

Tài liệu được tạo hiển thị đầy đủ thông tin và có thể mở lại từ danh sách tài liệu.

