---
title: "Self-Assessment"
date: 2026-11-25
weight: 6
chapter: false
pre: " <b> 6. </b> "
---

From **14 September 2026** to **14 December 2026**, I took part in the **Workforce Bootcamp – First Cloud AI Journey** program at **Amazon Web Services Viet Nam Company Limited**. I spent the first five weeks building a foundation in AWS: account security, VPC networking, EC2 with load balancing and Auto Scaling, S3/CloudFront, RDS, DynamoDB, containers on ECR/ECS, Lambda, Bedrock and Cognito. From mid-October I worked with three teammates on **TINA**, an AI meeting assistant. My own contributions were:

* **U1 connected meeting**: validated domain models, transactional storage, ASR and Bedrock adapters, single-use stream tickets, the Chrome extension capture and live-notes panel, and the speech runtime on AWS staging under a fixed budget.
* **Voice assistant (tina-speech)**: wake-word detection, a CPU TTS sidecar, authorized speaker turns between multiple clients, and tests for each part (PR #7).
* **Developer tooling**: a code knowledge graph of the monorepo with Graphify (PR #13) and Windows support for audio capture.
* **Post-meeting follow-up email**: branded emails with summary and recording links, and an encrypted SMTP configuration shared across services (PR #16, #17, #19).
* **Planning documents**: reviewing the target AWS architecture on ECS Fargate and writing the project proposal and cost estimate.

The biggest change for me was moving from writing code that works on my machine to shipping features that other people run: they must be tested, reviewed, documented, and cheap enough to keep running on a shared AWS account.

The table below is my own assessment of the internship:

| No. | Criteria | Description | Good | Fair | Average |
| --- | --- | --- | ---- | ---- | ------- |
| 1 | **Professional knowledge & skills** | AWS core services, real-time speech (STT/TTS), Bedrock integration, backend code quality | ✅ | ☐ | ☐ |
| 2 | **Ability to learn** | Picking up a large unfamiliar monorepo and new AWS services quickly | ✅ | ☐ | ☐ |
| 3 | **Proactiveness** | Building team tooling (code graph, Windows capture) without being asked | ✅ | ☐ | ☐ |
| 4 | **Sense of responsibility** | Finishing assigned features with tests and documentation | ✅ | ☐ | ☐ |
| 5 | **Discipline** | Keeping a steady pace and committing work regularly | ☐ | ✅ | ☐ |
| 6 | **Progressive mindset** | Acting on review comments and live-test failures | ✅ | ☐ | ☐ |
| 7 | **Communication** | Explaining designs and reporting progress to the team and mentors | ☐ | ✅ | ☐ |
| 8 | **Teamwork** | Reviewing teammates' pull requests and integrating with their work | ✅ | ☐ | ☐ |
| 9 | **Professional conduct** | Respecting colleagues, shared resources and the shared AWS budget | ✅ | ☐ | ☐ |
| 10 | **Problem-solving skills** | Debugging capture, microphone and concurrency issues found in real meetings | ✅ | ☐ | ☐ |
| 11 | **Contribution to project/team** | Voice assistant, follow-up email, U1 foundation, tooling, proposal | ✅ | ☐ | ☐ |
| 12 | **Overall** | General evaluation of the entire internship period | ✅ | ☐ | ☐ |

### Needs Improvement

* **Smaller, more frequent changes**: I sometimes held work locally for several days and pushed many commits at once (for example on 04/11 and 16/11). Smaller pull requests would make reviews easier and surface problems earlier.
* **More hands-on deployment on AWS**: most of my feature work ran on the self-hosted stack. I want more practice deploying and operating services on ECS Fargate, writing infrastructure as code, and reading CloudWatch metrics.
* **Measuring quality with numbers**: I tested the voice flow mainly by hand. I need repeatable measurements for wake-word accuracy, reply latency and email delivery.
* **Communication**: I should share progress and blockers earlier in team channels and present technical trade-offs more clearly, in both Vietnamese and English.
