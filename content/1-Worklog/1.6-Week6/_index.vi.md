---
title: "Tuần 6 - Thiết kế API và cấu trúc backend"
date: 2026-06-12
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

### Mục tiêu chính
Bước sang tuần 6, mình đi sâu vào xây dựng nền tảng backend vững chắc và cấu hình hạ tầng mạng trên AWS, tạo cơ sở để đưa ứng dụng lên cloud trong các tuần tới.

### Chi tiết công việc
1. Thiết lập dự án backend bằng Express.js, cấu hình các middleware chuẩn như xử lý CORS, ghi log và quản lý lỗi tập trung.
2. Phát triển các API đầu tiên cho tính năng quản lý Project và Task, đảm bảo dữ liệu trả về chuẩn xác trước khi ghép nối giao diện.
3. Cấu hình kiến trúc mạng (VPC): phân bổ public subnet cho EC2 và private subnet cho Amazon RDS theo sơ đồ đã thống nhất.
4. Triển khai PostgreSQL trên RDS, tùy chỉnh Security Group để chỉ cho phép truy cập từ EC2 và kiểm tra đường truyền kết nối thành công.

### Kết quả thu được
- Xây dựng thành công khung backend cơ bản cùng các API cốt lõi đầu tiên.
- Hoàn tất cấu trúc hạ tầng mạng thực tế bám sát nhu cầu triển khai đồ án.
- Hình dung được quy trình phát triển từ mã nguồn (code) kết hợp với cấu hình hạ tầng đám mây.

### Tham khảo
- [Data and Workflow Restructuring](https://000053.awsstudygroup.com/)
- [Database Essentials with Amazon Relational Database Service (RDS)](https://000005.awsstudygroup.com/)
- [Networking Essentials with Amazon Virtual Private Cloud (VPC)](https://000003.awsstudygroup.com/)
- [Building Microservices](https://000052.awsstudygroup.com/)
