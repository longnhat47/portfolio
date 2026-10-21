# Alex Morgan - Portfolio Website

Một trang web Portfolio hiện đại, chuẩn Responsive với dummy text chuyên nghiệp.

## Cấu trúc thư mục
- `index.html`: Giao diện chính của website (Hero, About, Skills, Projects, Services, Contact, Footer).
- `css/style.css`: Toàn bộ CSS với Dark Glassmorphism hiện đại, tối ưu cho Mobile & Desktop.
- `js/main.js`: Xử lý tương tác menu mobile, hiệu ứng chuyển tab, gửi form liên hệ dummy.
- `index.js`: Web server Node.js chính (zero-dependency), có sẵn `/health`, `/api/greeting`, graceful shutdown và tự động nhận `process.env.PORT` & `process.env.HOST` chuẩn Botkeep.
- `server.js`: Giữ tương thích ngược với lệnh cũ (`require('./index.js')`).
- `package.json`: Cấu hình lệnh khởi chạy `npm start` gọi `node index.js`.
- `.env.example`: File mẫu biến môi trường `HOST=0.0.0.0` và `PORT=3000`.

## Hướng dẫn triển khai lên Botkeep Cloud
1. **Cách 1: Triển khai bằng file ZIP (Đã nén chuẩn sẵn)**
   - Chọn file nén `portfolio.zip` tại mục **Source -> ZIP archive**.
   - Lưu ý: File nén đã chứa trực tiếp `index.js`, `package.json` ở cấp gốc (không bị bọc trong thư mục con).
2. **Cách 2: Triển khai từ GitHub**
   - Push toàn bộ code lên repository GitHub.
   - Kết nối GitHub repo với Botkeep. Botkeep sẽ tự động nhận diện file `index.js` và `package.json` tại root.
3. Nhấn **Deploy / Start server**. Server sẽ lắng nghe và tự động hoạt động mà không bị pause.
