---
title: "Worklog Tuần 11"
date: 2026-11-23
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---
### Mục tiêu tuần 11:

* Review kiến trúc AWS mục tiêu của nhóm cho TINA.
* Viết proposal dự án bằng tiếng Anh và tiếng Việt.
* Hoàn thiện ước tính chi phí và thực hành triển khai một service lên ECS Fargate.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Review kiến trúc AWS: CloudFront + WAF → ALB → các task ECS Fargate, RDS, ElastiCache, S3, Bedrock, SES. <br> - Góp ý luồng dữ liệu được đánh số. | 23/11/2026 | 23/11/2026 | [TINA repo](https://github.com/poor-frog/TINA) |
| 3 | - Viết proposal: tóm tắt, vấn đề, luồng kiến trúc, dịch vụ AWS, ngân sách (~148 USD/tháng), rủi ro và kết quả kỳ vọng. | 24/11/2026 | 24/11/2026 | [AWS Pricing Calculator](https://calculator.aws/) |
| 4 | - Chuyển lộ trình thành bảng theo tuần với công việc của từng thành viên. <br> - Fork repo báo cáo và viết lại worklog theo format FCAJ. | 25/11/2026 | 25/11/2026 |  |
| 5 | - Tạo bản ước tính trên AWS Pricing Calculator và gắn link vào proposal. <br> - Đặt cảnh báo AWS Budgets ở mức 50%, 80% và 100%. | 26/11/2026 | 26/11/2026 | [AWS Pricing Calculator](https://calculator.aws/) |
| 6 | - Triển khai container TTS từ ECR lên ECS Fargate, kiểm tra log CloudWatch rồi dọn dẹp tài nguyên. | 27/11/2026 | 27/11/2026 | [Amazon ECS Docs](https://docs.aws.amazon.com/ecs/) |

### Kết quả đạt được tuần 11:

* Review kiến trúc mục tiêu và đối chiếu từng luồng được đánh số với dịch vụ tương ứng.
* Hoàn thành proposal bằng hai ngôn ngữ, gồm bảng lộ trình theo tuần của nhóm.
* Chuyển báo cáo sang fork cá nhân với worklog được viết lại.
* Đang thực hiện: ước tính trên Pricing Calculator, cảnh báo ngân sách và lần triển khai ECS Fargate đầu tiên.
