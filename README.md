# AWS First Cloud AI Journey (FCAJ) - Internship Worklog

Đây là kho lưu trữ toàn bộ quá trình thực tập của mình trong chương trình **Workforce Bootcamp – First Cloud AI Journey** tại **Amazon Web Services (AWS) Việt Nam**.

Repository bao gồm các nội dung như:

- 📘 Worklog theo từng tuần thực tập.
- 📄 Proposal mô tả đề tài và kiến trúc hệ thống.
- ✍️ Các bài viết kỹ thuật (Technical Blogs).
- 🎤 Báo cáo các sự kiện và workshop đã tham gia.
- 📝 Báo cáo tự đánh giá sau quá trình thực tập.

Website được xây dựng bằng **Hugo Static Site Generator**, giúp quản lý tài liệu dễ dàng, tốc độ tải nhanh và thuận tiện khi triển khai lên nền tảng Cloud.

---

# Thông tin thực tập

| Nội dung | Thông tin |
|-----------|-----------|
| **Họ và tên** | Đinh Nguyễn Duy Thanh |
| **MSSV** | 703705421 |
| **Email** | 28.dndt@gmail.com |
| **Trường** | Đại học Công nghệ TP. Hồ Chí Minh (HUTECH) |
| **Chuyên ngành** | Công nghệ Thông tin |
| **Lớp** | 22DTHD7 |
| **Đơn vị thực tập** | Công ty TNHH Amazon Web Services Việt Nam |
| **Chương trình** | Workforce Bootcamp – First Cloud AI Journey |
| **Thời gian thực tập** | 20/04/2026 – 20/07/2026 |
| **Đề tài** | Website Bán Nhạc Cụ Saxophone |
| **Nhóm** | TTTN Team |

---

# Hướng dẫn chạy dự án trên máy cá nhân

Để xem website trên máy tính của bạn, hãy thực hiện các bước dưới đây.

## 1. Cài đặt Hugo

Dự án sử dụng **Hugo Extended**, vì vậy hãy cài đặt phiên bản phù hợp với hệ điều hành.

### Windows (Chocolatey)

```bash
choco install hugo-extended -confirm
```

### macOS (Homebrew)

```bash
brew install hugo
```

### Ubuntu / Debian

```bash
sudo apt install hugo
```

Sau khi cài đặt, hãy kiểm tra:

```bash
hugo version
```

---

## 2. Clone source code

Sao chép repository về máy:

```bash
git clone https://github.com/DuyThenh28/AWS_WorkShop_DuyThanh2909.git
```

Di chuyển vào thư mục dự án:

```bash
cd AWS_WorkShop_DuyThanh2909
```

---

## 3. Chạy website ở chế độ phát triển

Khởi động Hugo Server:

```bash
hugo server -D
```

Tham số `-D` sẽ hiển thị cả các nội dung đang ở trạng thái **Draft**.

---

## 4. Truy cập website

Sau khi server khởi động thành công, mở trình duyệt và truy cập:

```
http://localhost:1313
```

Mỗi khi bạn chỉnh sửa các tệp Markdown trong thư mục `content/`, Hugo sẽ tự động biên dịch lại và cập nhật giao diện ngay trên trình duyệt mà không cần khởi động lại server.

---

# Cấu trúc nội dung

```
content/
│
├── 1-Worklog/
├── 2-Proposal/
├── 3-BlogsPosted/
├── 4-EventParticipated/
├── 5-Workshop/
├── 6-Self-evaluation/
└── 7-Feedback/
```

---

# Công nghệ sử dụng

- Hugo Static Site Generator
- Markdown
- HTML
- CSS
- Git & GitHub
- AWS Cloud Services

---

# Mục tiêu dự án

Dự án được thực hiện nhằm ghi lại toàn bộ quá trình học tập, thực hành và triển khai các nội dung trong chương trình thực tập tại AWS. Đồng thời đây cũng là nơi tổng hợp các tài liệu, báo cáo và kết quả đạt được trong suốt thời gian tham gia chương trình.

---

# Tác giả

**Đinh Nguyễn Duy Thanh**

Cloud Intern – Workforce Bootcamp  
First Cloud AI Journey (FCAJ)  
Amazon Web Services Việt Nam
