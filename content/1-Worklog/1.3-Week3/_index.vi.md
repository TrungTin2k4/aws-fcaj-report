---
title: "Tuần 3 - Mạng nội bộ VPC và Database RDS"
date: 2026-05-22
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

### Mục tiêu chính
Tuần 3 là lúc chuyển mình từ việc dùng các dịch vụ đơn lẻ sang tư duy thiết kế kiến trúc. Trọng tâm là phân chia lớp mạng, bảo mật truy cập và thiết lập database trong vùng an toàn (private).

### Chi tiết công việc
1. Xây dựng một mạng VPC hoàn chỉnh với các public subnet dành cho máy chủ web và private subnet để cô lập cơ sở dữ liệu.
2. Cấu hình Internet Gateway, Route Table và tìm hiểu cơ chế định tuyến dữ liệu bên trong mạng nội bộ.
3. Khởi tạo hệ quản trị cơ sở dữ liệu PostgreSQL qua dịch vụ Amazon RDS, gắn vào private subnet và thiết lập Security Group tương ứng.
4. Đọc thêm tài liệu về dịch vụ phân giải tên miền Amazon Route 53 (mô hình Hybrid DNS) để có bức tranh toàn cảnh về cách định tuyến người dùng.

### Kết quả thu được
- Hiểu được tầm quan trọng của việc chia tách public/private subnet trong một VPC.
- Kết nối thành công máy chủ EC2 (public) với cơ sở dữ liệu RDS (private) một cách bảo mật.
- Nắm bắt được tư duy mở rộng kiến trúc hạ tầng mạng thực tế.

### Tham khảo
- [Database Essentials with Amazon Relational Database Service (RDS)](https://000005.awsstudygroup.com/)
- [Hybrid DNS Management with Amazon Route 53](https://000010.awsstudygroup.com/)
- [Networking Essentials with Amazon Virtual Private Cloud (VPC)](https://000003.awsstudygroup.com/)
