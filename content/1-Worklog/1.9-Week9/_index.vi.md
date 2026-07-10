---
title: "Worklog Tuần 9"
date: 2026-06-15
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Mục tiêu cho tuần 9:
* Trực quan hóa và triển khai thành công luồng xử lý dữ liệu âm thanh từ Mobile qua Amazon S3 và Amazon SQS.
* Định hình và cấu hình quy trình chuyển đổi giọng nói thành văn bản thông qua dịch vụ thông minh Amazon Transcribe.
* Đảm bảo dữ liệu sau chuyển đổi được lưu trữ an toàn, toàn vẹn vào hệ thống Amazon RDS.

### Nhiệm vụ cho tuần 9:

| Ngày | Nhiệm vụ | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| :---: | :--- | :---: | :---: | :--- |
| 2 | Thiết lập cổng đẩy file âm thanh từ ứng dụng di động lên lưu trữ tại Amazon S3. | 15/06/2026 | 16/06/2026 | [AWS SDK for Mobile Audio Upload](https://docs.aws.amazon.com/s3/) |
| 3 | Cấu hình Event Notification trên S3 kích hoạt đẩy thông điệp vào hàng đợi Amazon SQS. | 16/06/2026 | 17/06/2026 | [Amazon SQS Developer Guide](https://docs.aws.amazon.com/sqs/) |
| 4 | Nghiên cứu cơ chế bắt sự kiện từ SQS để gọi xử lý nhận dạng qua dịch vụ Amazon Transcribe. | 17/06/2026 | 18/06/2026 | [Amazon Transcribe Speech-to-Text](https://docs.aws.amazon.com/transcribe/) |
| 5 | Lập trình module tiếp nhận văn bản kết quả từ Transcribe, làm sạch định dạng dữ liệu. | 18/06/2026 | 19/06/2026 | [Data Processing in Node.js](https://nodejs.org/) |
| 6 | Viết câu lệnh lưu trữ kết quả văn bản cuối cùng vào bảng cơ sở dữ liệu trên Amazon RDS. | 19/06/2026 | 21/06/2026 | [RDS Data Persistence Guides](https://docs.aws.amazon.com/rds/) |

### Thành tích tuần 9:
* **Vận hành dịch vụ AWS:** Thiết lập chuỗi liên thông dịch vụ hoàn hảo bao gồm Amazon S3, SQS, Transcribe và RDS hoạt động đồng bộ.
* **Kỹ năng kỹ thuật:** Xây dựng thành công kiến trúc hướng sự kiện (Event-driven Architecture) xử lý tệp tin đa phương tiện trên môi trường đám mây.
* **Nền tảng kiến thức:** Làm chủ giải pháp ứng dụng trí tuệ nhân tạo (Speech-to-Text AI) vào bài toán thực tế giúp nâng cao đáng kể hiệu năng hệ thống.