---
title: "Week 2 Worklog"
date: 2026-09-21
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---
### Week 2 Objectives:

* Design and build a VPC with public and private subnets across two Availability Zones.
* Understand traffic control with route tables, security groups and network ACLs.
* Practice connecting to instances securely and keeping network costs low.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | - Study VPC, CIDR planning, subnets, route tables and the Internet Gateway. <br> - Build a VPC with 2 public and 2 private subnets in 2 AZs. | 21/09/2026 | 21/09/2026 | [cloudjourney.awsstudygroup.com](https://cloudjourney.awsstudygroup.com/)<br>[Amazon VPC Docs](https://docs.aws.amazon.com/vpc/latest/userguide/) |
| 3 | - Compare security groups (stateful) and network ACLs (stateless). <br> - Launch an EC2 instance in a public subnet and connect with a key pair. | 22/09/2026 | 22/09/2026 | [cloudjourney.awsstudygroup.com](https://cloudjourney.awsstudygroup.com/)<br>[Amazon VPC Docs](https://docs.aws.amazon.com/vpc/latest/userguide/) |
| 4 | - Add a NAT Gateway so private instances can reach the Internet. <br> - Connect to a private instance with Session Manager instead of a bastion host. <br> - Enable VPC Flow Logs to CloudWatch Logs. | 23/09/2026 | 23/09/2026 | [cloudjourney.awsstudygroup.com](https://cloudjourney.awsstudygroup.com/)<br>[Amazon VPC Docs](https://docs.aws.amazon.com/vpc/latest/userguide/) |
| 5 | - Learn VPC peering, Transit Gateway and Site-to-Site VPN at the concept level. <br> - Learn Route 53 hosted zones and basic routing policies. | 24/09/2026 | 24/09/2026 | [cloudjourney.awsstudygroup.com](https://cloudjourney.awsstudygroup.com/) |
| 6 | - Draw the lab VPC in draw.io. <br> - Delete the NAT Gateway and Elastic IP after the lab and check the bill. | 25/09/2026 | 25/09/2026 | [cloudjourney.awsstudygroup.com](https://cloudjourney.awsstudygroup.com/) |

### Week 2 Achievements:

* Built a two-AZ VPC with public/private subnets, IGW, NAT Gateway and working route tables.
* Chose correctly between security groups and network ACLs for each rule.
* Accessed private instances through Session Manager without opening SSH to the Internet.
* Learned that NAT Gateway and public IPv4 addresses are recurring costs and cleaned them up.
* Attended the Buildrathon Kickoff: Code the Future with CMC Global (26/09).
