---
title: "Worklog Tuần 8"
date: 2026-11-02
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---
### Mục tiêu tuần 8:

* Chuyển sang codebase TINA self-hosted mới của nhóm (meeting bot, phiên âm, agent).
* Xây dựng trợ lý giọng nói: nhận diện wake word, thu câu hỏi và trả lời bằng giọng nói.
* Viết test cho luồng speech và merge vào main.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Tìm hiểu codebase mới: meeting bot, transcript stream qua Redis và agent. <br> - Viết kế hoạch triển khai tina-speech gồm ba giai đoạn. | 02/11/2026 | 02/11/2026 | [TINA repo](https://github.com/poor-frog/TINA) |
| 3 | - Thử nghiệm giai đoạn 1: nhận diện wake word trên âm thanh cục bộ. <br> - Cố định phiên bản runtime và model KWS; ghi nhận kết quả giai đoạn 1 và 2. | 03/11/2026 | 03/11/2026 | [TINA repo](https://github.com/poor-frog/TINA) |
| 4 | - Thêm TTS sidecar chạy CPU (tùy chọn), giọng nữ, đọc đúng tên "Tina". <br> - Bot báo kết quả phát giọng nói; meeting service theo dõi các lượt phát tương ứng. | 04/11/2026 | 04/11/2026 | [TINA repo](https://github.com/poor-frog/TINA) |
| 5 | - Điều phối lượt nói được cấp quyền, tạm dừng host khi đang có lượt chung và rào quyền thu âm. <br> - Test wake gating, replay, phân xử nhiều client và khôi phục. <br> - Sửa pre-push gate chạy trên Windows. | 05/11/2026 | 05/11/2026 | [TINA repo](https://github.com/poor-frog/TINA) |
| 6 | - Giới hạn request TTS và giữ được việc hủy; thu cả câu hỏi bị KWS báo trễ. <br> - Nạp env mã hóa dùng chung bằng dotenvx. <br> - Merge PR #7 feat/tina-speech vào main. | 06/11/2026 | 06/11/2026 | [TINA PR #7](https://github.com/poor-frog/TINA/pull/7) |

### Kết quả đạt được tuần 8:

* Hoàn thành trợ lý giọng nói: gọi "Tina", đặt câu hỏi và nghe câu trả lời ngay trong cuộc họp.
* Xử lý tranh chấp: mỗi lúc chỉ có một lượt nói được cấp quyền, có khôi phục khi client rớt kết nối.
* Viết test cho wake gating, giao thức TTS, phát âm thanh và phân xử nhiều client.
* Merge tính năng vào main qua PR #7.
