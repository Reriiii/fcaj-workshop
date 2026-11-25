---
title: "Worklog Tuần 3"
date: 2026-09-28
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---
### Mục tiêu tuần 3:

* Triển khai ứng dụng web trên EC2 phía sau load balancer có tự động mở rộng.
* Dùng Amazon S3 và CloudFront để lưu trữ và phân phối nội dung an toàn.
* Tham dự buổi xem trực tiếp AWS Cloud & AI Day 2026.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Tìm hiểu các dòng EC2, AMI, ổ EBS gp3 và snapshot. <br> - Tạo web server bằng script user data. | 28/09/2026 | 28/09/2026 | [cloudjourney.awsstudygroup.com](https://cloudjourney.awsstudygroup.com/)<br>[Amazon EC2 Docs](https://docs.aws.amazon.com/ec2/) |
| 3 | - Tham dự AWS Cloud & AI Day 2026: HCMC Watch Party tại văn phòng AWS. <br> - Ghi chú các phiên về Agentic AI, phát triển phần mềm AI-native và bảo mật AI. | 29/09/2026 | 29/09/2026 | AWS Cloud & AI Day 2026 |
| 4 | - Tạo launch template và Auto Scaling group phía sau Application Load Balancer. <br> - Thử target tracking policy bằng cách tạo tải CPU. | 30/09/2026 | 30/09/2026 | [cloudjourney.awsstudygroup.com](https://cloudjourney.awsstudygroup.com/)<br>[Amazon EC2 Docs](https://docs.aws.amazon.com/ec2/) |
| 5 | - Thực hành S3: storage class, versioning, lifecycle rule và Block Public Access. <br> - Host website tĩnh trên S3. | 01/10/2026 | 01/10/2026 | [cloudjourney.awsstudygroup.com](https://cloudjourney.awsstudygroup.com/)<br>[Amazon S3 Docs](https://docs.aws.amazon.com/s3/) |
| 6 | - Đặt CloudFront với Origin Access Control phía trước S3 bucket private. <br> - So sánh EBS, EFS và S3 cho từng loại workload. | 02/10/2026 | 02/10/2026 | [cloudjourney.awsstudygroup.com](https://cloudjourney.awsstudygroup.com/)<br>[Amazon S3 Docs](https://docs.aws.amazon.com/s3/) |

### Kết quả đạt được tuần 3:

* Triển khai được tầng web có load balancer và Auto Scaling group tự tăng/giảm theo tải CPU.
* Phân phối nội dung từ S3 bucket private qua CloudFront với OAC thay vì để bucket công khai.
* Thiết lập versioning và lifecycle rule để chuyển object cũ sang lớp lưu trữ rẻ hơn.
* Có thêm góc nhìn về Agentic AI và phát triển phần mềm có AI hỗ trợ từ AWS Cloud & AI Day 2026.
