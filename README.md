# Hana Nguyen — Personal Portfolio & CV (`github.io`) - Phiên bản cập nhật (v2)

Trang web cá nhân được thiết kế theo phong cách **Odyssey Theme** (`treefarmstudio/odyssey-theme`) đã được cập nhật theo yêu cầu mới:
1. **Menu điều hướng chung `Projects`**: Đã đổi tên mục menu từ `Projects (HOC247 Kids)` thành **`Projects`** để dùng chung cho nhiều dự án sau này, đồng thời chuẩn bị sẵn khung mẫu (template) trong `projects.html` để bạn dễ dàng thêm `Project 02`, `Project 03`...
2. **Thay thế Logo chữ & Avatar bằng Hình ảnh (`profile.jpg`)**:
   - Cả phần **Logo góc trên bên trái** và **Thẻ hồ sơ ở trang chính (`index.html`)** đều đã được chuyển sang hiển thị **hình ảnh** (`<img src="profile.jpg" ...>`).
   - Đi kèm tệp ảnh mặc định `profile.svg` để trang web không bao giờ bị lỗi hiển thị ảnh trống. **Khi tải lên GitHub, bạn chỉ cần đặt tên bức ảnh cá nhân (hoặc ảnh logo) của mình là `profile.jpg` và tải vào cùng thư mục gốc**, trang web sẽ tự động hiển thị hình ảnh của bạn ở cả thanh điều hướng và khung giới thiệu chính!

## Cấu trúc thư mục
- `index.html`: Trang chủ giới thiệu bản thân, hiển thị hình ảnh đại diện/logo (`profile.jpg`), liên kết mạng xã hội (YouTube, LinkedIn, TikTok) và toàn bộ nội dung CV.
- `projects.html`: Trang danh sách các dự án (`Projects`), mở đầu với `Project 01: HOC247 Kids` kèm 3 video YouTube nhúng trực tiếp và phần khung chờ cho các dự án tiếp theo.
- `styles.css`: Tập tin giao diện CSS hỗ trợ 4 bảng màu lấy cảm hứng từ Odyssey Theme (Classic Forest, Ocean, Terracotta, Dark).
- `profile.svg`: Hình ảnh minh họa mặc định (sẽ tự động được thay thế ngay khi bạn tải file ảnh `profile.jpg` của mình lên).
