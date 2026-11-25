---
title: "Worklog Tuần 10"
date: 2026-11-16
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---
### Mục tiêu tuần 10:

* Hoàn thành email follow-up sau cuộc họp và cấu hình gửi mail.
* Review pull request của các thành viên.
* Chuẩn bị chuyển TINA từ EC2 + Docker Compose sang ECS Fargate.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Gửi email follow-up có nhận diện thương hiệu kèm link tài liệu; thêm cấu hình gửi qua Resend SMTP. <br> - Sửa lỗi gửi follow-up, tích hợp main và tách fixture test mail. <br> - Merge PR #13 (Graphify), PR #16 (email sau cuộc họp) và PR #17 (cấu hình gửi mail). | 16/11/2026 | 16/11/2026 | [TINA PR #16](https://github.com/poor-frog/TINA/pull/16)<br>[TINA PR #17](https://github.com/poor-frog/TINA/pull/17) |
| 3 | - Dùng chung cấu hình SMTP mã hóa giữa các service và viết tài liệu cách nạp cấu hình. <br> - Merge PR #19. | 17/11/2026 | 17/11/2026 | [TINA PR #19](https://github.com/poor-frog/TINA/pull/19) |
| 4 | - Review PR #20 (khôi phục báo cáo sau cuộc họp). <br> - So sánh SMTP/Resend với Amazon SES cho môi trường thật: sandbox, domain đã xác minh, DKIM, chi phí. | 18/11/2026 | 18/11/2026 | [TINA PR #20](https://github.com/poor-frog/TINA/pull/20)<br>[Amazon SES Docs](https://docs.aws.amazon.com/ses/) |
| 5 | - Tìm hiểu ECS Fargate cho TINA: mỗi service một task definition, service discovery, secrets. <br> - Tìm hiểu Cognito liên kết Google làm identity provider. | 19/11/2026 | 19/11/2026 | [Amazon ECS Docs](https://docs.aws.amazon.com/ecs/)<br>[Amazon Cognito Docs](https://docs.aws.amazon.com/cognito/) |
| 6 | - Thu thập giả định giá cho proposal: Fargate theo vCPU/GB-giờ, ALB, NAT Gateway, RDS, ElastiCache. | 20/11/2026 | 20/11/2026 | [AWS Pricing Calculator](https://calculator.aws/) |

### Kết quả đạt được tuần 10:

* Người tham dự nhận email follow-up có nhận diện thương hiệu kèm link tóm tắt và bản ghi sau mỗi cuộc họp.
* Cấu hình mail được mã hóa và dùng chung, mọi service gửi qua cùng một cấu hình.
* Merge bốn pull request (#13, #16, #17, #19) và review công việc của các thành viên.
* Có kế hoạch rõ ràng và số liệu đầu vào chi phí để chạy TINA trên ECS Fargate.
* Tham dự AWS Student Community Day Vietnam 2026 (21/11).
