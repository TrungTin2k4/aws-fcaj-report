---
title: "Event 2"
date: 2026-05-23
weight: 2
chapter: false
pre: " <b> 4.2. </b> "
---

# Bài thu hoạch Event 2

Sự kiện thứ hai mình tham gia tập trung sâu hơn vào các bài toán thực tế của doanh nghiệp, từ xu hướng việc làm, cách tối ưu công cụ LLM đến các giải pháp hạ tầng và AI cấp độ Enterprise. Dưới đây là những ghi chép đúc kết từ các phiên trình bày:

### 1. Xu hướng việc làm và cách thích ứng trong kỷ nguyên AI
**(Diễn giả: Nguyễn Gia Hưng - Solution Architect tại AWS Việt Nam)**

**Bối cảnh thị trường:** Sự bùng nổ của AI không làm giảm việc làm dài hạn, ngược lại, khi việc tạo phần mềm trở nên rẻ và dễ dàng hơn, nhu cầu xây dựng ứng dụng sẽ tăng vọt. Tuy nhiên, trong ngắn hạn, thị trường có sự dịch chuyển do các công ty tối ưu hóa chi phí để đầu tư cho AI, gây khó khăn cho người mới.

**Xu hướng việc làm mới:** Sẽ có sự gia tăng nhu cầu cho vai trò "fixer" – những kỹ sư chuyên sửa lỗi, bảo trì, vận hành và đưa các sản phẩm (MVP) do người không chuyên (dùng AI tạo ra) lên môi trường production thực tế.

**Yêu cầu mới để cạnh tranh:**
- **Nền tảng kỹ thuật vững chắc:** Kiến thức cốt lõi (như bằng đại học) vẫn cực kỳ quan trọng như một "tấm vé vào cửa".
- **Hiểu biết nghiệp vụ (Use cases):** Phải nắm được các bài toán thực tế của doanh nghiệp (ví dụ: ứng dụng AI trong tài chính, ngân hàng) chứ không chỉ dừng ở bài tập học thuật.
- **Có sản phẩm thực tế (Product mindset):** Khi đi phỏng vấn, nhà tuyển dụng sẽ đòi hỏi xem sản phẩm thực tế bạn đã làm được gì.

**Lời khuyên:** Đừng trì hoãn, hãy hành động ngay lập tức vì sức mạnh của AI đang tăng theo cấp số nhân mỗi 4 tháng.

### 2. Tối ưu hóa Context khi giao tiếp với LLM
**(Diễn giả: Tịnh Trương - Platform Engineer tại Got It)**

**Vấn đề phổ biến:** Người dùng thường có thói quen hỏi nhiều chủ đề khác nhau trong cùng một đoạn chat (session), khiến AI bị "loạn" ngữ cảnh (context) và trả lời không chính xác.

**Giải pháp - Xây dựng Context đúng:**
- **Context là ngữ cảnh:** Khi yêu cầu AI viết code cho một hệ thống ngân hàng, không cần giải thích lại những kiến thức chung trên mạng. Hãy cung cấp những tài liệu, quy chuẩn, blueprint nội bộ riêng biệt của công ty.
- **Các thành phần của Context tốt:** Bao gồm Mục tiêu (Goal), Vai trò của AI (Role), Người nhận thông tin (Audience - ví dụ: "Hãy giải thích cho tôi như người mới bắt đầu"), Định dạng đầu ra (Format/Style) và Bằng chứng/Tài liệu tham khảo (Evidence).
- **Cạm bẫy "Internet Puller":** Tránh tình trạng copy-paste bừa bãi các đoạn code, plugin hay context (Prompt injection) từ internet vào hệ thống mà không hiểu rõ. Việc đưa quá nhiều thông tin không liên quan sẽ khiến AI bị quá tải và xử lý sai lệch.

**Lời khuyên:** Hãy tìm hiểu về AI Mindset, AI Adoption và khái niệm Second Brain (tổ chức kiến thức cá nhân) để trở thành một kỹ sư có khả năng làm chủ công cụ AI thay vì bị công cụ điều khiển.

### 3. Giải quyết vấn đề doanh nghiệp bằng Amazon Q Business
**(Diễn giả: Hải Anh - Cloud Engineer tại Pacific Việt Nam)**

**Vấn đề:** Các nhà quản lý (Manager, C-level) tốn quá nhiều thời gian để tổng hợp dữ liệu, báo cáo từ nhiều nguồn khác nhau (Excel, Email, v.v.).

**Giải pháp - Amazon Q Business:** Đây là một nền tảng tạo trợ lý ảo (AI Agent) an toàn cho doanh nghiệp, tích hợp sẵn với hệ sinh thái dữ liệu nội bộ (Microsoft, Google).

**Tính năng chính (Demo):**
- Cho phép người dùng không có kỹ năng lập trình (như phân tích viên kinh doanh) tải một file Excel dữ liệu thô lên Amazon Q.
- AI sẽ tự động đọc hiểu dữ liệu và tạo ra các bảng biểu phân tích, biểu đồ (dashboard) trực quan.
- Người dùng có thể trò chuyện trực tiếp với dữ liệu bằng ngôn ngữ tự nhiên.
- **Khái niệm Agent và MCP:** AI Agent như một bộ não, cần các "cánh tay nối dài" là MCP (Model Context Protocol - một dạng plugin) để thực hiện các hành động thực tế (như đặt lịch họp, gửi email tóm tắt).

### 4. Amazon CloudFront: Không chỉ là CDN, mà là nền tảng bảo vệ và tối ưu
**(Diễn giả: Nguyễn Huỳnh Thịnh - DevOps Engineer)**

**Vấn đề với CDN truyền thống:** Khó kiểm soát chi phí Pay-as-you-go. Nếu web bị DDoS hoặc bỗng dưng nổi tiếng, lưu lượng tăng vọt có thể dẫn đến một tờ hóa đơn khổng lồ vào cuối tháng ("ngủ dậy thành con nợ").

**Giải pháp - Gói cước Cố định (Flat-rate Pricing):** CloudFront cung cấp các gói cước cố định. Nếu vượt quá lưu lượng, website chỉ bị bóp băng thông chứ không phát sinh thêm chi phí, giúp doanh nghiệp an tâm kiểm soát ngân sách.

**Tính năng bảo mật sâu của CloudFront:**
- **Ngăn chặn DDoS:** Nhờ hạ tầng 700 điểm hiện diện (PoP) toàn cầu, chặn đứng bot độc hại ngay tại nguồn quốc gia phát sinh, bảo vệ máy chủ gốc. Hỗ trợ chống SYN Flood.
- **VPC Origin:** Cho phép CloudFront kết nối thẳng vào máy chủ (EC2) nằm trong mạng nội bộ (Private Subnet) mà không cần đi qua internet, ẩn hoàn toàn hạ tầng khỏi hacker.
- **Geo-blocking:** Chặn truy cập từ các khu vực địa lý cụ thể.
- **Mutual TLS (mTLS):** Xác thực hai chiều cho các ứng dụng tài chính.
- **Tối ưu hiệu suất & Chi phí:** Tích hợp nén dữ liệu, HTTP/3, tối ưu TCP Handshake và chia sẻ tải cho server giúp tiết kiệm đáng kể chi phí truyền tải dữ liệu.

### 5. Góc nhìn về Multi-Agent System trong môi trường Enterprise
**(Diễn giả: Vy Lâm)**

**Bài toán thực tế:** Ngân hàng cần đánh giá tín dụng để cho vay các công ty Startup. Đây là bài toán khó vì Startup không có báo cáo tài chính 3 năm, không có tài sản thế chấp (chỉ có tài sản trí tuệ và đội ngũ sáng lập).

**Tại sao chọn Multi-Agent:** Dữ liệu đa chiều. Một AI Agent duy nhất (Single Agent) không thể đóng nhiều vai trò cùng lúc do giới hạn về Context Window và độ chuyên sâu (Expertise). Cần một hệ thống Multi-Agent: Phân tích tài chính, Nghiên cứu thị trường, Đánh giá đội ngũ, Đánh giá rủi ro và một Manager Agent để tổng hợp.

**Tính nghiêm ngặt của Enterprise:**
- **Bảo mật & Rủi ro:** Không thể cắm tùy tiện các tool bên ngoài (MCP) hay dùng mã nguồn mở không kiểm soát vì rủi ro rò rỉ dữ liệu hoặc Prompt Injection. Phải có cơ chế Guardrails, xoay vòng khóa API liên tục.
- **Trách nhiệm (Audit Trail):** Mọi quyết định có sự can thiệp của người dùng đều phải được lưu vết. Khi phê duyệt khoản vay bị sai, người chịu trách nhiệm trước pháp luật là nhân viên phê duyệt chứ không phải AI.
- **Kiến thức chuyên môn:** Phải biết cách trích xuất những kiến thức tinh túy nhất từ các chuyên gia tín dụng để dạy cho AI (Context Engineering), chứ không phải nhồi nhét tài liệu ngẫu nhiên.

**Lời khuyên:** Doanh nghiệp vẫn cực kỳ cần kỹ sư Backend vững tay nghề (để biết tích hợp API, bảo mật dữ liệu, mã hóa...) hơn là người chỉ biết AI bề nổi. Hãy xây dựng hệ thống theo 3 nguyên tắc: Reliably (Đáng tin cậy), Securely (Bảo mật) và Scalable (Mở rộng được).

---

### Ảnh minh chứng tham gia Event 2

![Email xác nhận đăng ký Event 2](/images/4-Event/event2/registration-email.png)
*Email xác nhận đăng ký tham gia FCAJ Community Day ngày 23/05/2026.*

![Vé QR tham gia Event 2](/images/4-Event/event2/ticket-qr.png)
*Mã QR check-in sự kiện tại Bitexco Financial Tower.*

![Không gian sự kiện Event 2](/images/4-Event/event2/event-room.png)
*Toàn cảnh khu vực tổ chức và người tham dự trước giờ bắt đầu chương trình.*

![Ảnh người tham dự Event 2](/images/4-Event/event2/audience-photo.png)
*Không khí theo dõi phần trình bày tại sự kiện.*

![Slide Proposed Deployment Approach](/images/4-Event/event2/deployment-approach-slide.png)
*Minh họa nội dung chia sẻ về hướng triển khai hệ thống ở mức enterprise.*

![Slide Basic Deployment Flow](/images/4-Event/event2/deployment-flow-slide.png)
*Sơ đồ flow triển khai cơ bản được trình bày trong workshop.*

![Slide Workshop Exercises](/images/4-Event/event2/workshop-exercises-slide.png)
*Nội dung các bài tập thực hành đi kèm trong buổi chia sẻ.*

![Ghi chú whiteboard tại Event 2](/images/4-Event/event2/whiteboard-note.png)
*Một số từ khóa trọng tâm được nhấn mạnh trong phần thảo luận: Security, Reliability, Scalable.*

> Nhìn chung, sự kiện mang lại góc nhìn thực tế, sâu sắc hơn về kiến trúc AI và điện toán đám mây cho quy mô doanh nghiệp.
