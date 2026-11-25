---
title: "Worklog Tuần 6"
date: 2026-10-19
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---
### Mục tiêu tuần 6:

* Chuyển phạm vi đã duyệt thành yêu cầu, user story và các unit of work.
* Thiết lập workspace AI-DLC và bộ nhận diện thương hiệu cho nhóm.
* Xây dựng phần nền của unit U1 (connected meeting).

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Phân tích yêu cầu, persona và user story. <br> - Chia sản phẩm thành 5 unit U1–U5 kèm sơ đồ phụ thuộc. | 19/10/2026 | 19/10/2026 | [TINA repo](https://github.com/poor-frog/TINA) |
| 3 | - Thiết lập workspace AI-DLC và chính sách model cho agent. <br> - Thêm bộ nhận diện TINA và design token. <br> - Ghi nhận contract yêu cầu và kế hoạch triển khai đã duyệt. | 20/10/2026 | 20/10/2026 | [TINA repo](https://github.com/poor-frog/TINA) |
| 4 | - Xây dựng domain model có validate và lớp storage có transaction. <br> - Xây dựng chủ sở hữu cuộc họp và trạng thái giao diện extension. | 21/10/2026 | 21/10/2026 | [TINA repo](https://github.com/poor-frog/TINA) |
| 5 | - Thêm adapter ASR (faster-whisper) và Bedrock có giới hạn tài nguyên. <br> - Đánh giá model Bedrock cho ghi chú theo chi phí và độ trễ; chọn Nova 2 Lite. | 22/10/2026 | 22/10/2026 | [TINA repo](https://github.com/poor-frog/TINA)<br>[Amazon Bedrock Docs](https://docs.aws.amazon.com/bedrock/) |
| 6 | - Xây dựng cơ chế dẫn xuất khóa có phiên bản cho stream ticket WebSocket dùng một lần. | 23/10/2026 | 24/10/2026 | [TINA repo](https://github.com/poor-frog/TINA) |

### Kết quả đạt được tuần 6:

* Hoàn thành tài liệu inception: yêu cầu, user story và các unit U1–U5.
* Hoàn thành phần code đầu tiên của U1: domain model, storage, quyền sở hữu cuộc họp và trạng thái extension.
* Kết nối backend với ASR và Bedrock qua adapter có giới hạn, chọn model Nova 2 Lite.
* Bảo vệ luồng âm thanh bằng stream ticket dùng một lần, có phiên bản.
* Tham dự First Cloud AI Journey Meet Up (24/10).
