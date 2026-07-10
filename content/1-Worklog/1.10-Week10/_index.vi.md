---
title: "Tuần 10 - Tự động hóa, xuất bản và tổng kết kỳ thực tập"
date: 2026-07-08
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Mục tiêu chính
Trong chặng cuối từ **06/07/2026** đến **25/07/2026**, mục tiêu tối thượng là hoàn thiện sản phẩm ở mức ổn định nhất, xuất bản ứng dụng ra công chúng (public) và chuẩn bị tài liệu báo cáo tổng kết.

### Chi tiết công việc
1. Viết một AWS Lambda function làm trigger cho Cognito: tự động đồng bộ thông vị user mới vào database (PostgreSQL) ngay sau khi xác thực thành công.
2. Tích hợp Cognito Authorizer vào API Gateway, buộc frontend phải đính kèm JWT token hợp lệ vào header khi gọi các API nhạy cảm.
3. Triển khai Frontend lên dịch vụ AWS Amplify Hosting, cấu hình domain, phân nhánh (branch), và biến môi trường để đảm bảo giao tiếp trơn tru với hệ thống API public.
4. Thực hiện kiểm thử toàn diện (End-to-End Test), rà soát lại giao diện, bổ sung đầy đủ nhật ký công việc, tổng hợp minh chứng và chốt hồ sơ báo cáo thực tập vào đúng hạn định 08/07.

### Kết quả thu được
- Hoàn chỉnh luồng tạo tài khoản, xác thực danh tính và phân quyền truy cập thông minh.
- Đưa frontend lên nền tảng public thành công, có thể dễ dàng trình diễn sản phẩm thực tế với nhà tuyển dụng/giáo viên hướng dẫn.
- Khép lại kỳ thực tập một cách trọn vẹn với đầy đủ cả kỹ năng thực hành, kỹ năng viết tài liệu và kinh nghiệm triển khai dự án thực tế.

### Tham khảo
- [CI/CD for Serverless Applications](https://000084.awsstudygroup.com/)
- [Serverless Automation with AWS Lambda](https://000022.awsstudygroup.com/)
- [Single Page Application Authentication](https://000055.awsstudygroup.com/)
- [Serverless Storage and Auth with AWS Amplify](https://000134.awsstudygroup.com/)
- [Frontend Integration with API Gateway](https://000135.awsstudygroup.com/)
