---
title: "Week 11 Worklog"
date: 2026-11-23
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---
### Week 11 Objectives:

* Review the team's target AWS architecture for TINA.
* Write the project proposal in English and Vietnamese.
* Finish the cost estimate and practice deploying a service on ECS Fargate.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | - Review the AWS architecture: CloudFront + WAF → ALB → ECS Fargate tasks, RDS, ElastiCache, S3, Bedrock, SES. <br> - Give feedback on the numbered data flow. | 23/11/2026 | 23/11/2026 | [TINA repo](https://github.com/poor-frog/TINA) |
| 3 | - Write the proposal: summary, problem, architecture flow, AWS services, budget (~$137/month), risks and outcomes. | 24/11/2026 | 24/11/2026 | [AWS Pricing Calculator](https://calculator.aws/) |
| 4 | - Turn the timeline into a weekly table with each member's tasks. <br> - Fork the report repository and rewrite the worklog in the FCAJ format. | 25/11/2026 | 25/11/2026 |  |
| 5 | - Create the cost estimate for the proposal in the AWS Pricing Calculator. <br> - Set AWS Budgets alerts at 50%, 80% and 100%. | 26/11/2026 | 26/11/2026 | [AWS Pricing Calculator](https://calculator.aws/) |
| 6 | - Deploy the TTS container from ECR to ECS Fargate, check CloudWatch logs, then clean up. | 27/11/2026 | 27/11/2026 | [Amazon ECS Docs](https://docs.aws.amazon.com/ecs/) |

### Week 11 Achievements:

* Reviewed the target architecture and mapped every numbered flow to a service.
* Completed the proposal in both languages, including the weekly team timeline.
* Moved the report to a personal fork with a rewritten worklog.
* Created the AWS Pricing Calculator estimate for the proposal and set AWS Budgets alerts at 50%, 80% and 100%.
* Deployed the TTS container from ECR to ECS Fargate, verified its logs in CloudWatch and cleaned up the resources afterwards.
