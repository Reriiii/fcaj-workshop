---
title: "Tự đánh giá"
date: 2026-11-25
weight: 6
chapter: false
pre: " <b> 6. </b> "
---

Từ ngày **14/09/2026** đến ngày **14/12/2026**, tôi tham gia chương trình **Workforce Bootcamp – First Cloud AI Journey** tại **Công ty TNHH Amazon Web Services Việt Nam**. Năm tuần đầu, tôi xây dựng nền tảng AWS: bảo mật tài khoản, mạng VPC, EC2 với load balancer và Auto Scaling, S3/CloudFront, RDS, DynamoDB, container trên ECR/ECS, Lambda, Bedrock và Cognito. Từ giữa tháng 10, tôi cùng ba thành viên khác làm dự án **TINA**, một trợ lý cuộc họp AI. Phần đóng góp của tôi gồm:

* **U1 connected meeting**: domain model có validate, lớp storage có transaction, adapter ASR và Bedrock, stream ticket dùng một lần, chức năng thu âm và panel ghi chú trực tiếp trên Chrome extension, và speech runtime chạy trên môi trường staging AWS trong ngân sách cố định.
* **Trợ lý giọng nói (tina-speech)**: nhận diện wake word, TTS sidecar chạy CPU, điều phối lượt nói được cấp quyền giữa nhiều client, kèm test cho từng phần (PR #7).
* **Công cụ cho nhóm phát triển**: knowledge graph cho code của monorepo bằng Graphify (PR #13) và hỗ trợ thu âm trên Windows.
* **Email follow-up sau cuộc họp**: email có nhận diện thương hiệu kèm link tóm tắt và bản ghi, cấu hình SMTP mã hóa dùng chung giữa các service (PR #16, #17, #19).
* **Tài liệu kế hoạch**: review kiến trúc AWS mục tiêu trên ECS Fargate, viết proposal và ước tính chi phí của dự án.

Thay đổi lớn nhất với tôi là chuyển từ viết code chạy được trên máy mình sang làm tính năng cho người khác dùng: phải có test, được review, có tài liệu và đủ rẻ để chạy trên tài khoản AWS dùng chung.

Bảng dưới đây là phần tự đánh giá của tôi về kỳ thực tập:

| STT | Tiêu chí | Mô tả | Tốt | Khá | Trung bình |
| --- | -------- | ----- | --- | --- | ---------- |
| 1 | **Kiến thức và kỹ năng chuyên môn** | Dịch vụ AWS cốt lõi, xử lý giọng nói thời gian thực (STT/TTS), tích hợp Bedrock, chất lượng code backend | ✅ | ☐ | ☐ |
| 2 | **Khả năng học hỏi** | Nắm nhanh một monorepo lớn chưa quen và các dịch vụ AWS mới | ✅ | ☐ | ☐ |
| 3 | **Chủ động** | Tự xây công cụ cho nhóm (code graph, thu âm Windows) mà không cần được giao | ✅ | ☐ | ☐ |
| 4 | **Tinh thần trách nhiệm** | Hoàn thành tính năng được giao kèm test và tài liệu | ✅ | ☐ | ☐ |
| 5 | **Kỷ luật** | Giữ nhịp làm việc đều và commit thường xuyên | ☐ | ✅ | ☐ |
| 6 | **Tính cầu tiến** | Sửa đổi theo góp ý review và lỗi phát hiện khi kiểm thử thật | ✅ | ☐ | ☐ |
| 7 | **Giao tiếp** | Giải thích thiết kế và báo cáo tiến độ cho nhóm và mentor | ☐ | ✅ | ☐ |
| 8 | **Hợp tác nhóm** | Review pull request của thành viên khác và tích hợp với phần việc của họ | ✅ | ☐ | ☐ |
| 9 | **Ứng xử chuyên nghiệp** | Tôn trọng đồng nghiệp, tài nguyên chung và ngân sách AWS dùng chung | ✅ | ☐ | ☐ |
| 10 | **Tư duy giải quyết vấn đề** | Xử lý lỗi thu âm, micro và tranh chấp đồng thời phát hiện trong cuộc họp thật | ✅ | ☐ | ☐ |
| 11 | **Đóng góp vào dự án/nhóm** | Trợ lý giọng nói, email follow-up, nền tảng U1, công cụ nhóm, proposal | ✅ | ☐ | ☐ |
| 12 | **Tổng thể** | Đánh giá chung về toàn bộ quá trình thực tập | ✅ | ☐ | ☐ |

### Cần cải thiện

* **Chia nhỏ thay đổi, đẩy code thường xuyên hơn**: có lúc tôi giữ code ở máy nhiều ngày rồi đẩy nhiều commit một lần (ví dụ ngày 04/11 và 16/11). Pull request nhỏ hơn sẽ giúp review dễ hơn và phát hiện lỗi sớm hơn.
* **Thực hành triển khai trên AWS nhiều hơn**: phần lớn tính năng của tôi chạy trên stack self-hosted. Tôi cần luyện thêm việc triển khai và vận hành service trên ECS Fargate, viết infrastructure as code và đọc metric trên CloudWatch.
* **Đo chất lượng bằng số liệu**: tôi chủ yếu kiểm thử luồng giọng nói bằng tay. Cần có cách đo lặp lại được cho độ chính xác wake word, độ trễ phản hồi và tỷ lệ gửi email thành công.
* **Giao tiếp**: cần chia sẻ tiến độ và vướng mắc sớm hơn trong kênh chung của nhóm, trình bày các đánh đổi kỹ thuật rõ ràng hơn bằng cả tiếng Việt và tiếng Anh.
