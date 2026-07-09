---
title: "Week 10 - Serverless Automation & Final Deployment"
date: 2026-07-08
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Week 10 Objectives:
* Automate data synchronization between Cognito and RDS utilizing AWS Lambda Triggers.
* Publicly host the Next.js application leveraging AWS Amplify Hosting.
* Enforce robust API security via Cognito Authorizers and finalize project documentation.

### Tasks to be implemented this week:
| Day | Task | Start Date | Completion Date | Reference |
| :--- | :--- | :--- | :--- | :--- |
| Mon | - Develop an **AWS Lambda (Post-Confirmation Trigger)** function in Node.js.<br>- Code the Lambda to perform a POST request to the EC2 Backend to persist newly authenticated User data. | 06/07/2026 | 06/07/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Tue | - Reinforce Backend protection: Implement a **Cognito Authorizer** within API Gateway.<br>- Update RTK Query interceptors to inject JWT tokens into protected API requests. | 07/07/2026 | 07/07/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Wed | - Set up an automated CI/CD pipeline for the Next.js app via **AWS Amplify Hosting**.<br>- Link the GitHub repository and configure Production build variables. | 08/07/2026 | 08/07/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Thu | - Finalize the project: Conduct a comprehensive review of all worklogs and verify the live demo environments for the final assessment. | 08/07/2026 | 08/07/2026 | |

### Week 10 Achievements:
* Achieved full automation for user onboarding by syncing Cognito identities with the PostgreSQL database via Lambda.
* Secured the entire backend infrastructure, enforcing JWT Authorization at the API Gateway layer.
* Successfully deployed the Next.js frontend globally with integrated CI/CD via AWS Amplify Hosting.
* Delivered the completed Capstone Project, fulfilling all internship requirements, and readied the final presentation.
