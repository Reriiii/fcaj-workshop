---
title: "Worklog Tuần 7"
date: 2026-10-26
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---
### Mục tiêu tuần 7:

* Hoàn thiện Chrome extension thu âm tab Google Meet và hiển thị ghi chú trực tiếp.
* Triển khai speech runtime và các cơ chế kiểm soát staging trên AWS.
* Kiểm thử với cuộc họp thật và giữ chi phí trong ngân sách đã thống nhất.

### Các công việc cần triển khai trong tuần này:

| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | - Xây dựng chức năng thu âm và panel ghi chú trực tiếp trong extension. <br> - Thiết kế lại giao diện meeting notebook và trạng thái sẵn sàng thu âm. | 26/10/2026 | 26/10/2026 | [TINA repo](https://github.com/poor-frog/TINA) |
| 3 | - Hoàn thiện runtime được bảo vệ và cơ chế kiểm soát staging bằng SAM. <br> - Thêm CI coverage theo phạm vi và kiểm tra hạ tầng cục bộ. <br> - Sửa trạng thái khởi động, khôi phục ASR bị gián đoạn và đối soát việc xóa dữ liệu. | 27/10/2026 | 27/10/2026 | [TINA repo](https://github.com/poor-frog/TINA) |
| 4 | - Triển khai speech runtime lên môi trường staging AWS. <br> - Tự động khôi phục các runtime bị dừng. | 28/10/2026 | 28/10/2026 | [TINA repo](https://github.com/poor-frog/TINA) |
| 5 | - Kiểm thử trực tiếp với cuộc họp Google Meet thật. <br> - Sửa lỗi thu âm và thiết lập micro; gia cố runtime thu âm và ghi chú. <br> - Merge baseline connected meeting và viết hướng dẫn onboarding. | 29/10/2026 | 29/10/2026 | [TINA repo](https://github.com/poor-frog/TINA) |
| 6 | - Thêm dashboard kiểm thử AWS có giới hạn thời gian. <br> - Ghi nhận chính sách ngân sách: trần 100 USD, chia 80 USD cho công việc và 20 USD cho dọn dẹp. <br> - Sửa ngữ cảnh speech liên tục và snapshot ghi chú; vẽ sơ đồ hệ thống TINA. | 30/10/2026 | 30/10/2026 | [TINA repo](https://github.com/poor-frog/TINA) |

### Kết quả đạt được tuần 7:

* Chạy được luồng end-to-end đầu tiên: Chrome extension → speech runtime trên AWS → ghi chú từ Bedrock → panel trực tiếp.
* Biết cách kiểm soát chi phí trên tài khoản dùng chung bằng lượt chạy có giới hạn thời gian, khoản giữ ngân sách và dự phòng dọn dẹp.
* Phát hiện và sửa các lỗi thu âm, micro chỉ xuất hiện trong cuộc họp thật.
* Tài liệu hóa hệ thống bằng sơ đồ kiến trúc draw.io và hướng dẫn onboarding.
* Tham dự AWS First Cloud AI Journey Community Day (31/10).
