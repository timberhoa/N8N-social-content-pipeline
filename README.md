# n8n Social Content Pipeline

Workflow n8n giúp tạo nội dung, duyệt ảnh qua Telegram, đặt lịch và tự đăng bài nhiều ảnh lên Facebook Page và Instagram.

## Chức năng

- Tạo nội dung và bộ ảnh bài đăng
- Lưu ảnh Google Drive
- Gửi Telegram để kiểm tra ảnh
- Duyệt và chọn ngày giờ đăng
- Đăng carousel Instagram
- Đăng bài nhiều ảnh Facebook Page
- Lưu lịch, trạng thái và link bài đăng vào Google Sheets

## Yêu cầu

- n8n self-hosted
- Meta App với quyền Facebook Page và Instagram
- Telegram Bot
- Google Drive và Google Sheets
- Các access token được cấu hình trong n8n Credentials

## Cài đặt

1. Tải file `social-content-pipeline.json`.
2. Import file vào n8n.
3. Tạo các credential riêng cho Meta, Telegram và Google.
4. Thay các giá trị `REPLACE_ME` hoặc các ID cấu hình trong workflow.
5. Chạy thử bằng dữ liệu mẫu trước khi bật workflow.

## Bảo mật

Không lưu access token, chatbot token, file `.env`, dữ liệu n8n hoặc dữ liệu khách hàng trong repository.
