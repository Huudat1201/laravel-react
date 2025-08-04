**Đề bài: Xây dựng Web Application Quản Lý Người Dùng**
Mô tả bài toán
Ứng viên cần xây dựng một web application với các tính năng:
1.	Đăng nhập/Đăng ký: Người dùng có thể tạo tài khoản và đăng nhập vào hệ thống.
2.	Quản lý người dùng: Cho phép admin quản lý danh sách user, xem thông tin chi tiết, cập nhật hoặc xóa user.
3.	Phân quyền: Hệ thống có ít nhất 2 loại tài khoản: 
o	Admin: Có quyền quản lý toàn bộ user.
o	User: Chỉ có quyền xem thông tin cá nhân và chỉnh sửa thông tin cá nhân của mình.
4.	Triển khai lên cloud: Ứng viên cần deploy hệ thống lên một dịch vụ cloud miễn phí để có thể truy cập từ internet.
5.	CI/CD với Jenkins: Thiết lập pipeline CI/CD để tự động build và deploy ứng dụng khi có thay đổi trong repo.
6.	Sử dụng Docker: Cấu hình Docker để quản lý backend và frontend.
________________________________________
**Yêu cầu kỹ thuật**
1. Backend (Laravel - PHP)
•	Sử dụng Laravel để xây dựng REST API phục vụ cho frontend.
•	Database: MySQL.
•	Cấu trúc API RESTful, bao gồm: 
o	Đăng ký & Đăng nhập (JWT hoặc Passport cho authentication).
o	CRUD user (chỉ Admin có quyền).
o	Xem & chỉnh sửa thông tin cá nhân (User).
2. Frontend (ReactJS)
•	Xây dựng giao diện bằng ReactJS.
•	Sử dụng thư viện tự chọn (Material UI, TailwindCSS, Bootstrap, v.v.).
•	Gọi API từ backend để thực hiện các chức năng: 
o	Đăng nhập, đăng ký.
o	Hiển thị danh sách user (chỉ Admin).
o	Chỉnh sửa thông tin cá nhân.
3. CI/CD với Jenkins
•	Thiết lập pipeline trên Jenkins để tự động: 
o	Build backend và frontend.
o	Deploy ứng dụng lên cloud.
4. Docker
•	Cấu hình Docker cho backend và frontend.
•	Sử dụng Docker Compose để quản lý các services.
5. Cloud Deployment
•	Ứng viên cần deploy ứng dụng lên một cloud service bất kì.
________________________________________
**Yêu cầu bổ sung**
•	Code phải clean, có cấu trúc tốt và dễ bảo trì.
•	Viết README.md hướng dẫn cách setup và chạy ứng dụng.
•	Cung cấp tài khoản admin để test.
•	Cấu hình environment variables an toàn.
