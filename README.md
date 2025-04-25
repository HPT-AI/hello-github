# 🧠 Hệ thống bán khóa học trực tuyến - Online Course Platform

Chào mừng đến với dự án hệ thống bán khóa học trực tuyến! Dự án này giúp bạn tạo một nền tảng để giảng viên đăng khóa học, học viên đăng ký, học và thanh toán dễ dàng.

## 🚀 Tính năng chính

- ✅ Đăng ký và đăng nhập người dùng (học viên & giảng viên)
- ✅ Quản lý khóa học, bài học và nội dung video
- ✅ Thanh toán online (Stripe/VNPAY/Momo)
- ✅ Hệ thống đánh giá, bình luận và theo dõi tiến độ học tập
- ✅ Giao diện thân thiện, hỗ trợ đa ngôn ngữ (Tiếng Việt / English)

## 🛠️ Công nghệ sử dụng

| Phần | Công nghệ |
|------|-----------|
| Frontend | React + TypeScript |
| Backend | ASP.NET Core Web API |
| Cơ sở dữ liệu | SQL Server |
| Hạ tầng | Docker, GitHub Actions, Redis, RabbitMQ |
| Monitoring | Prometheus + Grafana + ELK Stack |

## 📦 Cài đặt dự án (Local)

```bash
git clone https://github.com/ten_tai_khoan/course-platform.git
cd course-platform
docker-compose up --build
