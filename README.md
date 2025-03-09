<p align="center">
  <a href="https://expressjs.com/" target="blank"><img src="https://expressjs.com/images/express-facebook-share.png" width="120" alt="Express Logo" /></a>
</p>

# Express Server

📌 **Mô tả dự án**

Dự án này là một server API được xây dựng bằng Express.js.

📦 **Công nghệ sử dụng**

- **Backend:** Express.js, Node.js, MongoDB (hoặc PostgreSQL)
- **Quản lý môi trường:** dotenv
- **Bảo mật:** Helmet, CORS
- **Xác thực:** JWT (JSON Web Token)

🔧 **Cài đặt & Chạy dự án**

```bash
# 1. Clone dự án

git clone https://github.com/your-username/project-name.git
cd project-name

# 2. Cài đặt dependencies

npm install

# 3. Cấu hình biến môi trường

# Tạo file .env và thêm các thông tin sau:
PORT=5000
MONGO_URI=mongodb+srv://username:password@cluster.mongodb.net/dbname
JWT_SECRET=your_jwt_secret_key

# 4. Chạy server

npm start    # Chạy chế độ production
npm run dev  # Chạy chế độ development (hot reload với nodemon)
