Cần có nodejs, javac, maven

BE-Nodejs
node server.js : chạy server
npm install : cài thư viện


BE-Springboot
mvn clean install : cài đặt thư viện, build & kiểm lỗi
mvn spring-boot:run : chạy ứng dụng
mvn test : kiểm tra lỗi và chạy test

FE-React
npm run dev : chạy ở chế độ dev
npm run preview : chạy thử nghiệm trước khi up lên server(người khác có thể truy cập)
npm run build : chạy project, up to server (deploy lên server)

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
