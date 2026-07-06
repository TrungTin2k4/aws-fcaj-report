---
title: "Tuần 9 - Quản lý ảnh và xác thực tài khoản Cognito"
date: 2026-07-03
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Mục tiêu chính
Trải nghiệm người dùng được nâng cấp đáng kể trong tuần này với 2 tính năng chính: quản lý ảnh đại diện / ảnh đính kèm và xây dựng hệ thống đăng ký / đăng nhập an toàn.

### Chi tiết công việc
1. Thiết lập Amazon S3 bucket làm nơi lưu trữ các tập tin tĩnh (hình ảnh), sau đó cập nhật lại các đường dẫn hiển thị trên frontend.
2. Khởi tạo dịch vụ Amazon Cognito User Pool, thiết lập App Client cùng các quy tắc xác thực tài khoản (độ dài mật khẩu, email verification).
3. Sử dụng thư viện Amplify UI Components để tích hợp nhanh giao diện Đăng ký / Đăng nhập, tối ưu hóa thời gian phát triển frontend.
4. Kiểm thử luồng gửi email xác thực và cấu hình cách frontend lấy, lưu trữ token (session) sau khi đăng nhập thành công.

### Kết quả thu được
- Hệ thống lưu trữ hình ảnh trên S3 hoạt động trơn tru, giúp tách biệt dữ liệu tĩnh khỏi máy chủ backend.
- Luồng xác thực tài khoản được thiết lập bài bản, tăng cường độ bảo mật cho ứng dụng quản lý dự án.
- Sản phẩm ngày càng hoàn thiện, tiến gần hơn tới tiêu chuẩn của một ứng dụng thương mại.

### Tham khảo
- [Serverless Storage and Auth with AWS Amplify](https://000134.awsstudygroup.com/)
- [User Authentication with Amazon Cognito](https://000081.awsstudygroup.com/)
- [Single Page Application Authentication](https://000055.awsstudygroup.com/)
- [Cross-Domain Authentication with Amazon Cognito](https://000141.awsstudygroup.com/)
- [Static Website Hosting with Amazon S3](https://000057.awsstudygroup.com/)
