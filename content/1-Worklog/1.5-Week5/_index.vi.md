---
title: "Worklog Tuần 5"
date: 2026-10-12
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---
### Mục tiêu tuần 5:

* Tìm hiểu các thành phần serverless: Lambda và API Gateway.
* Khởi động dự án TINA, xác định vấn đề, phạm vi và ràng buộc theo quy trình AI-DLC.
* Tìm hiểu Amazon Bedrock và Amazon Cognito phục vụ dự án.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Xây một HTTP API nhỏ bằng API Gateway và Lambda. <br> - Tìm hiểu execution role, timeout, layer và log CloudWatch của Lambda. | 12/10/2026 | 12/10/2026 | [cloudjourney.awsstudygroup.com](https://cloudjourney.awsstudygroup.com/)<br>[AWS Lambda Docs](https://docs.aws.amazon.com/lambda/) |
| 3 | - Tìm hiểu Amazon Bedrock: model access, Converse API, giá theo token. <br> - Tìm hiểu Cognito user pool, hosted UI và luồng authorization code + PKCE. | 13/10/2026 | 13/10/2026 | [Amazon Bedrock Docs](https://docs.aws.amazon.com/bedrock/)<br>[Amazon Cognito Docs](https://docs.aws.amazon.com/cognito/) |
| 4 | - Khởi tạo repo TINA. <br> - Intent capture: vấn đề, nhóm thí điểm mục tiêu, kết quả mong muốn và tiêu chí thành công. | 14/10/2026 | 14/10/2026 | [TINA repo](https://github.com/poor-frog/TINA) |
| 5 | - Đánh giá khả thi: constraint register và RAID log. <br> - Ràng buộc chính: 200 USD credits Free Plan, quyền truy cập model Bedrock, xin đồng ý trước khi thu âm cuộc họp. | 15/10/2026 | 15/10/2026 | [TINA repo](https://github.com/poor-frog/TINA) |
| 6 | - Xác định phạm vi theo MoSCoW: ghi chú trực tiếp, task Notion có duyệt và agent hiểu ngữ cảnh cuộc họp là Must Have. <br> - Ghi nhận các hạng mục loại trừ và mốc 31/10 cho bản phát hành đầu. | 16/10/2026 | 16/10/2026 | [TINA repo](https://github.com/poor-frog/TINA) |

### Kết quả đạt được tuần 5:

* Xây dựng và kiểm thử endpoint Lambda + API Gateway, đọc được log trên CloudWatch.
* Khởi động TINA và hoàn thành giai đoạn ý tưởng: intent statement, đánh giá khả thi và backlog có thứ tự ưu tiên.
* Xác định sớm các rủi ro chính: credits có hạn, quyền truy cập model và quyền riêng tư dữ liệu cuộc họp.
* Hiểu Bedrock và Cognito phù hợp thế nào với kiến trúc dự kiến.
