# BTL_TTNT
Phần 1: Hướng dẫn cài đặt và chạy chương trình
1. Yêu cầu hệ thống
Hệ điều hành: Windows / Linux / macOS
Python phiên bản 3.8 trở lên
NodeJS phiên bản 16 trở lên
SQL Server 
Trình duyệt web (Google Chrome, Edge, Firefox)
Kết nối Internet để cài thư viện
2. Kiến trúc hệ thống
Hệ thống được xây dựng theo mô hình tách biệt:
Frontend (ReactJS)  →  Backend (NodeJS API)  →  Database (SQL Server)
Frontend: giao diện người dùng
Backend: xử lý logic, API
Database: lưu trữ dữ liệu
3. Các công cụ sử dụng
Ngôn ngữ lập trình: Python
Frontend:
ReactJS: Dùng để làm website (trang chủ, giỏ hàng, thanh toán...)
Axios: Dùng để gọi dữ liệu từ backend(ví dụ: lấy danh sách sách, gửi đơn hàng)
React Router: Dùng để chuyển trang(Home → Chi tiết sách → Giỏ hàng)
Backend:
NodeJS: Nền tảng chạy JavaScript phía server
ExpressJS: Framework để tạo API(ví dụ: /login, /books, /order
bcrypt (mã hóa mật khẩu)
JWT (xác thực người dùng)
Database:
SQL Server
Công cụ:
Visual Studio Code:Dùng để viết code frontend và backend, chỉnh sửa file và quản lý project
Postman:Dùng để test API backend (đăng nhập, giỏ hàng, đơn hàng,...)
GitHub:Dùng để lưu trữ và quản lý mã nguồ
4. Hướng dẫn cài đặt
Bước 1: Cài đặt Python

Tải và cài đặt Python tại trang chính thức: https://www.python.org
Kiểm tra sau khi cài: python --version
Sau đó cài: Cài NodeJS
Tải: https://nodejs.org
Kiểm tra:
node -v
npm -v
Bước 2: Tải mã nguồn
git clone <link-github> Hoặc tải file .zip và giải nén.
Bước 3: Cài Backend
cd backend
npm install
Bước 4: Cài Frontend
cd frontend
npm install
Bước 5: Cấu hình Database
Mở SQL Server
Import file .sql
Cập nhật file cấu hình backend:
config/db.js
5. Hướng dẫn chạy chương trình
Chạy Backend: 
cd backend
node server.js
Chạy Frontend
cd frontend:
npm start
6. Hướng dẫn sử dụng
Người dùng có thể thao tác:
Đăng ký / đăng nhập
Xem danh sách sách
Tìm kiếm sách
Xem chi tiết (mô tả, giá, đánh giá)
Thêm vào giỏ hàng
Thanh toán (COD hoặc chuyển khoản)
Đánh giá sản phẩm
Sử dụng chatbox hỗ trợ
7. Ghi chú
Nếu lỗi thư viện:
npm install
Nếu trùng port:
PORT=3001 npm start
Nếu không kết nối được database:
Kiểm tra config
Kiểm tra SQL Server đã chạy
Phần 2: Link dữ liệu, link code trên github và link Video
1. Link dữ liệu:


2. Link và Mã QR Github:



3. Link video Youtube báo cáo và demo kết quả:
