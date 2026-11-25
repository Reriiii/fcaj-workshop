---
title: "Worklog Tuần 2"
date: 2026-09-21
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---
### Mục tiêu tuần 2:

* Thiết kế và dựng VPC có public và private subnet trên hai Availability Zone.
* Hiểu cách kiểm soát lưu lượng bằng route table, security group và network ACL.
* Thực hành kết nối tới máy chủ an toàn và giữ chi phí mạng ở mức thấp.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Tìm hiểu VPC, quy hoạch CIDR, subnet, route table và Internet Gateway. <br> - Dựng VPC gồm 2 public và 2 private subnet trên 2 AZ. | 21/09/2026 | 21/09/2026 | [cloudjourney.awsstudygroup.com](https://cloudjourney.awsstudygroup.com/)<br>[Amazon VPC Docs](https://docs.aws.amazon.com/vpc/latest/userguide/) |
| 3 | - So sánh security group (stateful) và network ACL (stateless). <br> - Tạo EC2 trong public subnet và kết nối bằng key pair. | 22/09/2026 | 22/09/2026 | [cloudjourney.awsstudygroup.com](https://cloudjourney.awsstudygroup.com/)<br>[Amazon VPC Docs](https://docs.aws.amazon.com/vpc/latest/userguide/) |
| 4 | - Thêm NAT Gateway để máy chủ private ra được Internet. <br> - Kết nối máy chủ private bằng Session Manager thay cho bastion host. <br> - Bật VPC Flow Logs đẩy về CloudWatch Logs. | 23/09/2026 | 23/09/2026 | [cloudjourney.awsstudygroup.com](https://cloudjourney.awsstudygroup.com/)<br>[Amazon VPC Docs](https://docs.aws.amazon.com/vpc/latest/userguide/) |
| 5 | - Tìm hiểu ở mức khái niệm VPC peering, Transit Gateway và Site-to-Site VPN. <br> - Tìm hiểu hosted zone và các routing policy cơ bản của Route 53. | 24/09/2026 | 24/09/2026 | [cloudjourney.awsstudygroup.com](https://cloudjourney.awsstudygroup.com/) |
| 6 | - Vẽ lại VPC của bài lab bằng draw.io. <br> - Xóa NAT Gateway và Elastic IP sau khi lab xong, kiểm tra lại hóa đơn. | 25/09/2026 | 25/09/2026 | [cloudjourney.awsstudygroup.com](https://cloudjourney.awsstudygroup.com/) |

### Kết quả đạt được tuần 2:

* Dựng được VPC hai AZ với public/private subnet, IGW, NAT Gateway và route table hoạt động đúng.
* Chọn đúng giữa security group và network ACL cho từng quy tắc.
* Truy cập máy chủ private qua Session Manager mà không mở SSH ra Internet.
* Nhận ra NAT Gateway và địa chỉ IPv4 công khai là chi phí cố định nên đã dọn dẹp sau lab.
* Tham dự sự kiện Buildrathon Kickoff: Code the Future with CMC Global (26/09).
