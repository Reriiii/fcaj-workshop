---
title: "Week 10 Worklog"
date: 2026-11-16
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---
### Week 10 Objectives:

* Ship the post-meeting follow-up email and the mail delivery configuration.
* Review teammates' pull requests.
* Prepare for moving TINA from EC2 + Docker Compose to ECS Fargate.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | - Send branded meeting follow-ups with artifact links; add configurable Resend SMTP delivery. <br> - Fix follow-up delivery, integrate main and isolate mail test fixtures. <br> - Merge PR #13 (Graphify), PR #16 (post-meeting email) and PR #17 (mail delivery config). | 16/11/2026 | 16/11/2026 | [TINA PR #16](https://github.com/poor-frog/TINA/pull/16)<br>[TINA PR #17](https://github.com/poor-frog/TINA/pull/17) |
| 3 | - Share the encrypted SMTP configuration between services and document how it is loaded. <br> - Merge PR #19. | 17/11/2026 | 17/11/2026 | [TINA PR #19](https://github.com/poor-frog/TINA/pull/19) |
| 4 | - Review PR #20 (restore post-meeting reports). <br> - Compare SMTP/Resend with Amazon SES for production: sandbox, verified domain, DKIM, cost. | 18/11/2026 | 18/11/2026 | [TINA PR #20](https://github.com/poor-frog/TINA/pull/20)<br>[Amazon SES Docs](https://docs.aws.amazon.com/ses/) |
| 5 | - Study ECS on Fargate for TINA: one task definition per service, service discovery, secrets. <br> - Study Cognito federation with Google as the identity provider. | 19/11/2026 | 19/11/2026 | [Amazon ECS Docs](https://docs.aws.amazon.com/ecs/)<br>[Amazon Cognito Docs](https://docs.aws.amazon.com/cognito/) |
| 6 | - Collect pricing assumptions for the proposal: Fargate vCPU/GB-hours, ALB, NAT Gateway, RDS, ElastiCache. | 20/11/2026 | 20/11/2026 | [AWS Pricing Calculator](https://calculator.aws/) |

### Week 10 Achievements:

* Attendees now receive a branded follow-up email with summary and recording links after each meeting.
* Mail settings are encrypted and shared, so every service sends through the same configuration.
* Merged four pull requests (#13, #16, #17, #19) and reviewed teammates' work.
* Have a clear plan and cost inputs for running TINA on ECS Fargate.
* Attended AWS Student Community Day Vietnam 2026 (21/11).
