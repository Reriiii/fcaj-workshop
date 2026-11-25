---
title: "Worklog Tuần 4"
date: 2026-10-05
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---
### Mục tiêu tuần 4:

* Áp dụng nguyên tắc quyền tối thiểu với IAM policy và role.
* Thực hành cơ sở dữ liệu managed: RDS, DynamoDB và ElastiCache.
* Tìm hiểu container trên AWS (ECR, ECS, Fargate).
* Lập nhóm dự án và chọn ý tưởng.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Viết IAM policy bằng JSON và kiểm tra bằng IAM Policy Simulator. <br> - Gắn instance profile để EC2 đọc S3 mà không cần access key. | 05/10/2026 | 05/10/2026 | [cloudjourney.awsstudygroup.com](https://cloudjourney.awsstudygroup.com/)<br>[AWS IAM Docs](https://docs.aws.amazon.com/iam/) |
| 3 | - Tạo RDS PostgreSQL trong private subnet và kết nối từ EC2. <br> - So sánh Multi-AZ và read replica; thử automated backup và khôi phục. | 06/10/2026 | 06/10/2026 | [cloudjourney.awsstudygroup.com](https://cloudjourney.awsstudygroup.com/)<br>[Amazon RDS Docs](https://docs.aws.amazon.com/rds/) |
| 4 | - Thiết kế bảng DynamoDB với partition/sort key và GSI; dùng chế độ on-demand. <br> - Tìm hiểu ElastiCache for Redis làm cache và pub/sub. | 07/10/2026 | 07/10/2026 | [cloudjourney.awsstudygroup.com](https://cloudjourney.awsstudygroup.com/) |
| 5 | - Build Docker image và đẩy lên Amazon ECR. <br> - Tìm hiểu khái niệm ECS: cluster, task definition, service, Fargate. | 08/10/2026 | 08/10/2026 | [cloudjourney.awsstudygroup.com](https://cloudjourney.awsstudygroup.com/)<br>[Amazon ECS Docs](https://docs.aws.amazon.com/ecs/) |
| 6 | - Lập nhóm: Trần Kiến Quốc, Thái Việt Nam, Hoàng Đình Quang, Lê Hoài Thanh Quang. <br> - Brainstorm ý tưởng và chọn đề tài trợ lý cuộc họp AI tự động ghi chú và follow-up. | 09/10/2026 | 09/10/2026 |  |

### Kết quả đạt được tuần 4:

* Thay access key trên EC2 bằng IAM role và kiểm tra policy bằng simulator.
* Chạy RDS PostgreSQL trong private subnet và khôi phục được từ automated backup.
* Đẩy được container image lên ECR và hiểu cách ECS chạy image đó trên Fargate.
* Lập nhóm bốn người và thống nhất hướng dự án: trợ lý cuộc họp AI.
