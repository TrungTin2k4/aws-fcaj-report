---
title: "Tuần 8 - Đưa hệ thống Backend lên môi trường EC2"
date: 2026-06-26
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

### Mục tiêu chính
Tuần 8 là cột mốc quan trọng khi đưa backend từ môi trường thử nghiệm (local) lên đám mây (cloud). Ngoài việc cài đặt môi trường chạy mã nguồn, mình cũng giải quyết các bài toán về bảo mật giao tiếp (HTTPS) và duy trì tiến trình chạy nền.

### Chi tiết công việc
1. Tạo một máy chủ EC2 mới, điều chỉnh quy tắc Security Group, kết nối qua SSH và cài đặt nền tảng Node.js.
2. Triển khai mã nguồn backend lên EC2, sử dụng PM2 để quản lý và duy trì tiến trình ứng dụng luôn hoạt động 24/7.
3. Cập nhật các biến môi trường, đảm bảo máy chủ EC2 có thể kết nối thông suốt với cơ sở dữ liệu RDS qua Prisma.
4. Sử dụng Amazon API Gateway làm lớp trung gian (proxy) bọc ngoài backend, giúp frontend giao tiếp bảo mật qua HTTPS (tránh lỗi mixed content).

### Kết quả thu được
- Backend chính thức hoạt động trên môi trường cloud ổn định và độc lập.
- Nắm rõ cách đóng gói, cấu hình môi trường và vận hành một ứng dụng thực tế trên Linux.
- Giải quyết thành công rào cản kết nối bảo mật nhờ sự hỗ trợ của API Gateway.

### Tham khảo
- [Deploying Node.js Applications](https://000112.awsstudygroup.com/)
- [Frontend Integration with API Gateway](https://000135.awsstudygroup.com/)
- [Compute Essentials with Amazon Elastic Compute Cloud (EC2)](https://000004.awsstudygroup.com/)
- [Command Line Operations with AWS CLI](https://000011.awsstudygroup.com/)
