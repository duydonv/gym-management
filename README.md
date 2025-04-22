# Gym Management System

Hệ thống quản lý phòng tập thể hình với các chức năng quản lý thành viên, huấn luyện viên và gói tập.

## Các vai trò trong hệ thống

### 1. Admin
- Quản lý toàn bộ hệ thống
- Quản lý nhân viên và huấn luyện viên
- Quản lý gói tập và khuyến mãi
- Quản lý thiết bị tập luyệnluyện
- Xem báo cáo và thống kê

### 2. Huấn luyện viên
- Quản lý lịch huấn luyện
- Tạo và quản lý bài tập cho học viên
- Theo dõi tiến độ học viên

### 3. Thành viên
- Đăng ký và quản lý gói tập
- Xem và đặt lịch huấn luyện
- Theo dõi tiến độ tập luyện

## Cài đặt và chạy dự án

### Yêu cầu hệ thống
- Node.js (v14 trở lên)
- MongoDB
- npm hoặc yarn

### Bước 1: Cài đặt MongoDB
1. Tải và cài đặt MongoDB Community Edition
2. Khởi động MongoDB service

### Bước 2: Cài đặt dependencies
1. Cài đặt dependencies cho backend (tại thư mục gốc):
```bash
npm install
```

2. Cài đặt dependencies cho frontend:
```bash
cd client
npm install
```

### Bước 4: Chạy dự án
1. Khởi động backend server (tại thư mục gốc):
```bash
npm run dev
```

2. Khởi động frontend (trong terminal mới):
```bash
cd client
npm run dev
```

3. Truy cập ứng dụng:
- Frontend: http://localhost:5173
- Backend API: http://localhost:3000

