# 🔐 Spring Security JWT Authentication

## 📌 Giới thiệu
Dự án này triển khai **Spring Boot** kết hợp **Spring Security** và **JWT (JSON Web Token)** để xây dựng cơ chế **xác thực và phân quyền** an toàn cho API.  
Hệ thống hoạt động theo cơ chế **stateless** (không lưu session trên server) và sử dụng JWT để xác minh danh tính người dùng.

## 🚀 Tính năng
- 📄 Đăng ký & đăng nhập người dùng.
- 🔑 Sinh **Access Token** & **Refresh Token**.
- ✅ Xác thực người dùng bằng JWT cho mọi request.
- 🛡️ Phân quyền truy cập API theo vai trò.
- ⏳ Hết hạn token và cơ chế làm mới (refresh).
- ⚡ Tích hợp Spring Security Filter để kiểm tra token.

## 🏗️ Kiến trúc
