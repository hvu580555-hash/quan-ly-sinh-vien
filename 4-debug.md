```markdown

\# Bước 4: Kiểm tra và sửa lỗi (Debug)

\- \*\*Lỗi phát sinh 1:\*\* Người dùng để trống ô nhập liệu khi thêm sinh viên dẫn đến dữ liệu `undefined`.

&#x20; - \*Cách khắc phục:\* Thêm điều kiện kiểm tra `if (!id || !name)` và hiển thị cảnh báo `alert` trước khi thêm.

\- \*\*Lỗi phát sinh 2:\*\* Khi xóa phần tử giữa mảng, chỉ số index bị lệch.

&#x20; - \*Cách khắc phục:\* Sử dụng hàm `filter()` hoặc phương thức `splice(index, 1)` chính xác theo vị trí hàng được chọn.

\- \*\*Lỗi phát sinh 3:\*\* Giao diện bị tràn trên màn hình điện thoại nhỏ.

&#x20; - \*Cách khắc phục:\* Bổ sung thuộc tính `flex-wrap: wrap` và `meta viewport` để responsive tốt hơn.

