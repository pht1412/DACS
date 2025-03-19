Gõ lệnh npm run dev (nhớ cd vào FE) để chạy dự án

BE-SpringBoot là BE chính: Quản lý hệ thống tài khoản, sản phẩm, đơn hàng, Database
BE-Nodejs là BE phụ: 1 số API nhẹ(chat real-time), xử lý ảnh,

Cách thức làm việc
BE-Nodejs: server.js(khởi động server và định nghĩa API)
Thêm folder: routes, controllers, models, config (nếu cần)

BE-SpringBoot: src/main/java/com/primeshop
controllers, services, repositories, models
pom.xml: Quản lý thư viện

FE-React: src/
components, pages, services, App.tsx
vite.config.ts: Điều chỉnh config của React