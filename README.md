# Student Management System

## 1. Thông tin sinh viên

* Họ tên: Hồ Long Giang
* MSSV: 23694641
---

# 2. Giới thiệu project

Project **Student Management System** là một web app đơn giản giúp quản lý sinh viên.

Ứng dụng cho phép:

* Thêm sinh viên
* Xem danh sách sinh viên
* Chỉnh sửa thông tin sinh viên
* Xóa sinh viên
* Tìm kiếm sinh viên
* Thống kê dữ liệu
* Xuất dữ liệu CSV

Project được phát triển theo phương pháp **Vibe Coding với AI**, trong đó AI hỗ trợ sinh code và chỉnh sửa nghiệp vụ.

---

# 3. Tech Stack

### Backend

* FastAPI
* SQLAlchemy
* SQLite

### Frontend

* HTML
* Jinja2 Templates
* Bootstrap

### Database

* SQLite

---

# 4. Tools sử dụng

Các công cụ AI hỗ trợ trong quá trình phát triển:

* ChatGPT

Các tools hỗ trợ coding:

* VS Code
* Git
* GitHub

---

# 6. Database Schema

### Student

| Field      | Type    |
| ---------- | ------- |
| student_id | String  |
| name       | String  |
| birth_year | Integer |
| major      | String  |
| gpa        | Float   |
| class_id   | String  |

### Class

| Field      | Type   |
| ---------- | ------ |
| class_id   | String |
| class_name | String |
| advisor    | String |

Quan hệ:

```
Class 1 ---- n Student
```

Một lớp có nhiều sinh viên.

---

# 7. Các chức năng

## 7.1 Quản lý sinh viên

* Thêm sinh viên
* Sửa thông tin sinh viên
* Xóa sinh viên
* Hiển thị danh sách sinh viên

---

## 7.2 Tìm kiếm

Cho phép tìm kiếm sinh viên theo:

* Tên sinh viên

---

## 7.3 Thống kê

Dashboard hiển thị:

* Tổng số sinh viên
* GPA trung bình
* Số sinh viên theo ngành

---

## 7.4 Export dữ liệu

Cho phép xuất danh sách sinh viên ra file:

```
students.csv
```
---

# 8. Log thực hiện project

### Phiên bản 1 – MVP

Chức năng:

* Thêm sinh viên
* Xem danh sách sinh viên
* Sửa sinh viên
* Xóa sinh viên

Database:

* SQLite
* bảng Student

---

### Phiên bản 2 – Mở rộng

Thêm các chức năng:

* Bảng Class
* Mỗi sinh viên thuộc một lớp
* Tìm kiếm sinh viên
* Thống kê dashboard
* Export CSV

---
