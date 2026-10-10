# OverTheWire Bandit - Walkthrough & Writeups

## 📌 Giới thiệu về Bandit
**Bandit** là một wargame nổi tiếng được phát triển bởi tổ chức [OverTheWire](https://overthewire.org/wargames/bandit/). Đây là chuỗi thử thách thiết kế dành cho người mới bắt đầu học về hệ điều hành Linux, quản trị hệ thống và các khái niệm cơ bản trong An toàn thông tin / An ninh mạng.

Mục tiêu chính của wargame này là tìm mật khẩu của cấp độ tiếp theo bằng cách khai thác các dòng lệnh, tệp tin, quyền truy cập hoặc các dịch vụ mạng ở cấp độ hiện tại.

---

## 🎯 Các chủ đề & Kỹ năng cốt lõi

Thông qua các thử thách trong Bandit, repository này tổng hợp và thực hành các nhóm kỹ năng bao gồm:

* **Thao tác cơ bản với Linux:** Quản lý thư mục, tệp ẩn, tệp có tên đặc biệt và tra cứu tài liệu lệnh (`man`, `find`, `ls`, `cd`, `cat`).
* **Xử lý và lọc dữ liệu:** Sử dụng các công cụ tìm kiếm, sắp xếp và lọc chuỗi văn bản nâng cao (`grep`, `sort`, `uniq`, `strings`, `tr`, `cut`).
* **Định dạng & Giải nén:** Làm việc với dữ liệu nén nhiều lớp, mã hóa hex và nén đa định dạng (`tar`, `gzip`, `bzip2`, `xxd`).
* **Mã hóa căn bản:** Giải mã các chuỗi dữ liệu bị biến đổi như Base64, ROT13.
* **Mạng máy tính & Dịch vụ:** Tương tác với cổng mạng, truyền tải dữ liệu mã hóa SSL/TLS (`netcat`, `nmap`, `openssl`).
* **Quản lý quyền & SSH:** Đăng nhập qua SSH với cổng tùy chỉnh, sử dụng SSH Key (`ssh -i`), phân quyền tệp tin và tìm hiểu về các tiến trình chạy ngầm (`cron`, SUID/SGID).
* **Git & Version Control:** Khai thác lịch sử commit, làm việc với các nhánh (branch) và khôi phục dữ liệu từ Git repository.

---

## 📁 Cấu trúc Repository

Repository được tổ chức theo từng thư mục tương ứng với các cấp độ thử thách:

* `bandit0/` đến `bandit33/`: Chứa lệnh thực thi, ghi chép kỹ thuật và lời giải chi tiết cho từng Level tương ứng.

---

## 🚀 Kết nối tới Bandit

Để tham gia thử thách Bandit từ Terminal:

```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
