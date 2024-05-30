# Project 2: Website Motor24h quản lý dịch vụ du lịch và cho thuê xe máy
## Mô tả hê thống
Website Motor24h hướng tới đối tượng người dùng là những khách hàng có niềm đam mê phượt và cả bên quản lý dịch vụ. Ứng dụng cho phép khách hàng có thể đặt tour, thuê xe máy, thanh toán, thêm vào danh mục yêu thích, 
đánh giá dich vụ,... Đối với bên quản lý, hệ thống cung cấp các tính năng để quản lý tour, xe, quản lý đơn thuê, quản lý bảo dưỡng, sửa chữa.

## Các công nghệ sử dụng:
- Front-end: ReactJS, NextJS, TailwindCSS, DaisyUI, Redux Toolkit
- Backend: NestJS
- Database: MongoDB
- Cloud storage: Cloudinary

## Mô tả các chức năng chính 
Khách hàng: 
- Đăng ký, đăng nhập vào hệ thống 
- Đặt tour du lịch xe máy, tích hợp thanh toán VNPay
- Thuê xe máy, tích hợp thanh toán VNPay
- Hỗ trợ đánh giá, nhận xét về các tour du lịch, dịch vụ thuê xe
- Thêm tour hoặc xe máy vào danh mục yêu thích
- Xem danh sách tour du lịch, xe đã thuê, cập nhật thông tin cá nhân

Quản trị viên:
- Thêm mới, cập nhật tour du lịch, xe máy
- Quản lý đơn đặt tour du lịch, thuê xe của người dùng
- Quản lý tình trạng xe
- Quản lý bảo dưỡng, sửa chữa xe
- Import dữ liệu về xe máy từ file excel
- Export đơn thuê của khách hàng ra file PDF
