---
title: "Week 4 Worklog"
date: 2026-10-05
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---
### Week 4 Objectives:

* Apply least privilege with IAM policies and roles.
* Practice managed databases: RDS, DynamoDB and ElastiCache.
* Learn containers on AWS (ECR, ECS, Fargate).
* Form the project team and pick a project idea.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | - Write IAM policies in JSON and test them with the IAM Policy Simulator. <br> - Attach an instance profile so EC2 reads S3 without access keys. | 05/10/2026 | 05/10/2026 | [cloudjourney.awsstudygroup.com](https://cloudjourney.awsstudygroup.com/)<br>[AWS IAM Docs](https://docs.aws.amazon.com/iam/) |
| 3 | - Create RDS PostgreSQL in a private subnet and connect from EC2. <br> - Compare Multi-AZ and read replicas; test automated backups and restore. | 06/10/2026 | 06/10/2026 | [cloudjourney.awsstudygroup.com](https://cloudjourney.awsstudygroup.com/)<br>[Amazon RDS Docs](https://docs.aws.amazon.com/rds/) |
| 4 | - Model a DynamoDB table with partition/sort keys and a GSI; use on-demand capacity. <br> - Learn ElastiCache for Redis as a cache and pub/sub layer. | 07/10/2026 | 07/10/2026 | [cloudjourney.awsstudygroup.com](https://cloudjourney.awsstudygroup.com/) |
| 5 | - Build a Docker image and push it to Amazon ECR. <br> - Learn ECS concepts: cluster, task definition, service, Fargate launch type. | 08/10/2026 | 08/10/2026 | [cloudjourney.awsstudygroup.com](https://cloudjourney.awsstudygroup.com/)<br>[Amazon ECS Docs](https://docs.aws.amazon.com/ecs/) |
| 6 | - Form the team: Trần Kiến Quốc, Thái Việt Nam, Hoàng Đình Quang, Lê Hoài Thanh Quang. <br> - Brainstorm ideas and choose an AI meeting assistant that takes notes and follow-ups automatically. | 09/10/2026 | 09/10/2026 |  |

### Week 4 Achievements:

* Replaced access keys on EC2 with an IAM role and verified policies with the simulator.
* Ran RDS PostgreSQL in a private subnet and restored it from an automated backup.
* Pushed a container image to ECR and understood how ECS runs it on Fargate.
* Formed a four-member team and agreed on the project direction: an AI meeting assistant.
