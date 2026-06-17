# Car Dealership

A full-stack web application for managing a car dealership, including customer-facing storefront and an admin dashboard.

---

## Project Structure

```
car-dealership/
├── server/          # Backend - Node.js + Express + MongoDB
├── client-customer/ # Frontend dành cho khách hàng
└── client-admin/    # Frontend dành cho quản trị viên
```

---

## ⚙️ Tech Stack

| Layer     | Technology                     |
|-----------|-------------------------------|
| Backend   | Node.js, Express.js            |
| Database  | MongoDB, Mongoose              |
| Auth      | JWT (JSON Web Token)           |
| Email     | NodeMailer                     |
| Frontend  | React.js                       |

---

## Getting Started

### 1. Clone repository

```bash
git clone https://github.com/anhvu2409/car-dealership.git
cd car-dealership
```

### 2. Cài đặt & chạy Server

```bash
cd server
npm install
npm start
```

### 3. Cài đặt & chạy Client Customer

```bash
cd client-customer
npm install
npm start
```

### 4. Cài đặt & chạy Client Admin

```bash
cd client-admin
npm install
npm start
```

---

## Biến môi trường (Environment Variables)

Tạo file `.env` trong thư mục `server/` với nội dung:

```env
PORT=9999
MONGODB_URI=mongodb://localhost:27017/car-dealership
JWT_SECRET=your_jwt_secret
EMAIL_USER=your_email@gmail.com
EMAIL_PASS=your_email_password
```

---

## Tính năng

### Khách hàng
- Xem danh sách xe
- Tìm kiếm & lọc xe theo hãng, giá, năm sản xuất
- Đăng ký / Đăng nhập tài khoản
- Đặt lịch xem xe
- Liên hệ tư vấn

### Quản trị viên
- Quản lý danh sách xe (thêm, sửa, xóa)
- Quản lý đơn hàng
- Quản lý tài khoản khách hàng
- Thống kê doanh thu

---

## 👥 Thành viên nhóm

| Tên | Vai trò |
|-----|---------|
| Anh Vu | Fullstack Developer |

---