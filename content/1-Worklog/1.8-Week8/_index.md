---
title: "Week 8 - EC2 Backend Deployment"
date: 2026-06-28
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

### Week 8 Objectives:
* Migrate the Backend application to an Amazon EC2 instance.
* Guarantee continuous server execution utilizing PM2.
* Resolve Mixed Content issues by setting up an HTTPS proxy via Amazon API Gateway.

### Tasks to be implemented this week:
| Day | Task | Start Date | Completion Date | Reference |
| :--- | :--- | :--- | :--- | :--- |
| Mon | - Provision **Amazon EC2 (Amazon Linux 2023)** within the Public Subnet.<br>- Adjust the EC2 Security Group to permit Port 22 (SSH) and Port 80 (HTTP) traffic. | 22/06/2026 | 22/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Tue | - Establish SSH access, then install the Node.js runtime, NVM, and Git.<br>- Clone the backend repository and configure **PM2** for process management. | 23/06/2026 | 23/06/2026 | |
| Wed | - Define environment variables on the EC2 instance to link with Amazon RDS.<br>- Execute `npx prisma generate` to apply database migrations on the cloud. | 24/06/2026 | 24/06/2026 | |
| Thu | - Configure **Amazon API Gateway (REST API)** with a `/{proxy+}` resource.<br>- Establish an **HTTP Proxy Integration** routing traffic to the EC2 server and configure CORS. | 25/06/2026 | 25/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Fri | - Publish the API Gateway to a `prod` stage to obtain a secure HTTPS endpoint.<br>- Update the Frontend environment variables to route API calls through the API Gateway URL. | 26/06/2026 | 26/06/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Week 8 Achievements:
* Successfully transitioned the Node.js backend to a stable Amazon EC2 environment managed by PM2.
* Verified seamless database connectivity from the EC2 instance to the private RDS cluster.
* Addressed HTTP/HTTPS Mixed Content constraints completely by wrapping the EC2 instance with an Amazon API Gateway proxy.
