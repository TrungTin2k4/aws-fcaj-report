---
title: "Event 2"
date: 2026-05-23
weight: 2
chapter: false
pre: " <b> 4.2. </b> "
---

# Event 2 Insights

The second event I attended focused more deeply on practical enterprise problems, ranging from job trends and LLM optimization to infrastructure solutions and Enterprise-level AI. Below are the summarized notes from the presentations:

### 1. Employment Trends and Adaptation in the AI Era
**(Speaker: Nguyen Gia Hung - Solution Architect at AWS Vietnam)**

**Market Context:** The AI boom will not reduce long-term employment; conversely, as creating software becomes cheaper and easier, the demand for building applications will skyrocket. However, in the short term, there is a market shift as companies optimize costs to invest in AI, making it challenging for newcomers.

**New Job Trends:** There will be an increased demand for the "fixer" role—engineers specializing in debugging, maintaining, operating, and pushing products (MVPs) created by non-experts using AI into actual production environments.

**New Competitive Requirements:**
- **Solid Technical Foundation:** Core knowledge (like a university degree) remains extremely important as an "entry ticket."
- **Business Understanding (Use cases):** You must grasp practical enterprise problems (e.g., AI applications in finance and banking), not just academic exercises.
- **Practical Products (Product mindset):** During interviews, employers will want to see actual products you have built.

**Advice:** Do not procrastinate. Take action immediately because AI's power is increasing exponentially every 4 months.

### 2. Optimizing Context When Communicating with LLMs
**(Speaker: Tinh Truong - Platform Engineer at Got It)**

**Common Problem:** Users often ask about multiple distinct topics in a single chat session, causing the AI to lose context and provide inaccurate answers.

**Solution - Building the Right Context:**
- **Context is king:** When asking an AI to write code for a banking system, there is no need to re-explain general internet knowledge. Instead, provide the company's specific internal documents, standards, and blueprints.
- **Components of a Good Context:** Include the Goal, the AI's Role, the Audience (e.g., "Explain it to me like a beginner"), Output Format/Style, and Evidence/References.
- **The "Internet Puller" Trap:** Avoid blindly copy-pasting code snippets, plugins, or context (Prompt injection) from the internet into the system without understanding them. Providing too much irrelevant information overloads the AI and skews results.

**Advice:** Learn about the AI Mindset, AI Adoption, and the concept of a Second Brain (personal knowledge management) to become an engineer who masters AI tools rather than being controlled by them.

### 3. Solving Enterprise Problems with Amazon Q Business
**(Speaker: Hai Anh - Cloud Engineer at Pacific Vietnam)**

**The Problem:** Managers and C-level executives spend too much time consolidating data and reports from various sources (Excel, Email, etc.).

**Solution - Amazon Q Business:** This is a secure platform for creating AI Agents for enterprises, seamlessly integrated with internal data ecosystems (Microsoft, Google).

**Key Features (Demo):**
- Allows users without programming skills (such as business analysts) to upload a raw Excel data file to Amazon Q.
- The AI automatically understands the data and generates analytical tables and visual dashboards.
- Users can converse directly with the data using natural language.
- **Agent and MCP Concepts:** An AI Agent acts like a brain and needs "extended arms" called MCPs (Model Context Protocol - a type of plugin) to execute real-world actions (like scheduling meetings or sending summary emails).

### 4. Amazon CloudFront: Not Just a CDN, but a Protection and Optimization Platform
**(Speaker: Nguyen Huynh Thinh - DevOps Engineer)**

**The Problem with Traditional CDNs:** It's difficult to control Pay-as-you-go costs. If a website faces a DDoS attack or suddenly goes viral, traffic spikes can lead to a massive bill at the end of the month ("waking up in debt").

**Solution - Flat-rate Pricing:** CloudFront offers fixed-rate packages. If traffic exceeds the limit, the website's bandwidth is throttled rather than incurring additional costs, giving businesses peace of mind regarding budget control.

**Deep Security Features of CloudFront:**
- **DDoS Prevention:** Thanks to a global infrastructure of 700 Points of Presence (PoPs), malicious bots are blocked at their originating countries, protecting the origin server. Supports SYN Flood mitigation.
- **VPC Origin:** A powerful feature allowing CloudFront to connect directly to a server (EC2) inside a Private Subnet without routing over the public internet, completely hiding the infrastructure from hackers.
- **Geo-blocking:** Blocks access from specific geographical regions.
- **Mutual TLS (mTLS):** Two-way authentication for highly secure financial applications.
- **Performance & Cost Optimization:** Incorporates data compression, HTTP/3, optimized TCP Handshakes, and server load sharing, significantly reducing data transfer out costs.

### 5. Perspectives on Multi-Agent Systems in an Enterprise Environment
**(Speaker: Vy Lam)**

**Practical Business Problem:** Banks need to assess credit to lend to Startups. This is challenging because Startups lack a 3-year financial report and collateral (only having intellectual property and the founding team).

**Why Multi-Agent?** This problem involves multidimensional data. A single AI Agent cannot play multiple roles simultaneously due to Context Window limitations and required expertise. A Multi-Agent system is needed: Financial Analysis, Market Research, Team Assessment, Risk Evaluation, and a Manager Agent for consolidation.

**Enterprise Strictness:**
- **Security & Risk:** In banking, you cannot arbitrarily plug in external tools (MCPs) or use uncontrolled open-source code due to data leakage risks or Prompt Injection. Guardrails and continuous API Key Rotation mechanisms are mandatory.
- **Audit Trail (Accountability):** Any decision involving human intervention must be logged. If a large loan approval goes wrong, the human approver is legally responsible, not the AI.
- **Knowledge Transfer:** You must extract the most refined knowledge from real credit experts to teach the AI (Context Engineering), rather than randomly stuffing hundreds of document pages into it.

**Orientation Advice:** Enterprises (like banks) still heavily need highly skilled Backend engineers (who understand API integration, data security, encryption, etc.) far more than someone who only knows AI superficially. Build systems based on 3 principles: Reliably, Securely, and Scalably.

---

### Event Participation Evidence

![Event 2 Registration Confirmation Email](/images/4-Event/event2/registration-email.png)
*Registration confirmation email for FCAJ Community Day on 23/05/2026.*

![Event 2 QR Ticket](/images/4-Event/event2/ticket-qr.png)
*QR code for event check-in at Bitexco Financial Tower.*

![Event 2 Audience Photo](/images/4-Event/event2/audience-photo.jpg)
*The atmosphere during the presentations.*

![Basic Deployment Flow Slide](/images/4-Event/event2/deployment-flow-slide.jpg)
*Basic deployment flow diagram presented in the workshop.*

![Workshop Exercises Slide](/images/4-Event/event2/workshop-exercises-slide.jpg)
*Content of practical exercises included in the session.*

![Whiteboard Notes at Event 2](/images/4-Event/event2/whiteboard-note.jpg)
*Key terms highlighted during discussions: Security, Reliability, Scalable.*

> Overall, the event provided a highly practical and profound perspective on AI architecture and cloud computing at the enterprise scale.
