---
title: "Week 9 - Amazon S3 & Cognito Identity Integration"
date: 2026-06-30
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Week 9 Objectives:
* Manage and host static image assets securely via Amazon S3.
* Implement robust user identity management leveraging Amazon Cognito.
* Embed authentication flows into the Next.js app using AWS Amplify UI.

### Tasks to be implemented this week:
| Day | Task | Start Date | Completion Date | Reference |
| :--- | :--- | :--- | :--- | :--- |
| Mon | - Provision an **Amazon S3 Bucket** dedicated to static asset storage.<br>- Modify the S3 Bucket Policy to permit public `s3:GetObject` access. | 29/06/2026 | 29/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Tue | - Create an **Amazon Cognito User Pool**.<br>- Define security policies (passwords, MFA) and register an App Client. | 30/06/2026 | 30/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| Wed | - Integrate `aws-amplify` and `@aws-amplify/ui-react` libraries into the Frontend.<br>- Implement the standard **Authenticator UI** component provided by AWS. | 01/07/2026 | 01/07/2026 | |
| Thu | - Customize the Authenticator component to capture required registration attributes: Email, Username, and Password. | 02/07/2026 | 02/07/2026 | |
| Fri | - Validate the end-to-end email verification sequence powered by Cognito.<br>- Securely manage the `NEXT_PUBLIC_COGNITO_USER_POOL_ID` variable in the application. | 03/07/2026 | 03/07/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Week 9 Achievements:
* Successfully offloaded all static visual assets to Amazon S3, updating the Frontend to serve images globally.
* Instituted a comprehensive user identity management system via an Amazon Cognito User Pool.
* Integrated a polished, secure registration and login experience using Amplify UI, significantly saving development time.
