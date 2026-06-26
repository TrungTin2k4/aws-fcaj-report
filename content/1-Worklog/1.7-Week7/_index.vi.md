---
title: "Tuần 7 - Hoàn thiện Frontend và tích hợp nội bộ"
date: 2026-06-19
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

### Mục tiêu chính
Khi phần core backend đã thành hình, trọng tâm tuần này dịch chuyển sang mảng giao diện người dùng. Mục đích là tạo ra một ứng dụng có thể tương tác đầy đủ trên môi trường máy tính cá nhân (local) trước khi triển khai lên đám mây.

### Chi tiết công việc
1. Xây dựng giao diện frontend với Next.js và Tailwind CSS, tập trung vào thiết kế các component tái sử dụng cho hệ thống dashboard.
2. Ứng dụng RTK Query để quản lý và tối ưu hóa quá trình gọi API, thay thế cho các phương pháp fetch dữ liệu thủ công.
3. Hoàn thiện các giao diện cốt lõi: Dashboard tổng quan, chế độ xem Board, Table và Timeline phục vụ cho việc quản lý tiến độ.
4. Ghép nối trực tiếp Frontend với Backend ở môi trường local, xử lý triệt để các lỗi liên quan đến Hydration và đồng bộ dữ liệu.

### Kết quả thu được
- Giao diện người dùng cơ bản đã hoàn thiện, sẵn sàng cho các bài kiểm thử.
- Củng cố thêm kỹ năng quản lý state (trạng thái ứng dụng) và xử lý giao tiếp bất đồng bộ.
- Việc kiểm thử tích hợp nội bộ giúp lọc bỏ phần lớn lỗi logic trước khi bước vào giai đoạn đưa lên production.

### Tham khảo
- [Frontend Development for Serverless APIs](https://000079.awsstudygroup.com/)
- [Modernize the application Overview](https://cloudjourney.awsstudygroup.com/4-modernize/)
- [Single Page Application Authentication](https://000055.awsstudygroup.com/)
