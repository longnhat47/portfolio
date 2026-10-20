# Alex Morgan - Portfolio Website

Một trang web Portfolio hiện đại, chuẩn Responsive với dummy text chuyên nghiệp.

## Cấu trúc thư mục
- `index.html`: Giao diện chính của website (Hero, About, Skills, Projects, Services, Contact, Footer).
- `css/style.css`: Toàn bộ CSS với Dark Glassmorphism hiện đại, tối ưu cho Mobile & Desktop.
- `js/main.js`: Xử lý tương tác menu mobile, hiệu ứng chuyển tab, gửi form liên hệ dummy.
- `server.js`: Web server nhẹ viết bằng Node.js thuần (zero-dependency), tự động nhận `process.env.PORT` khi deploy lên Botkeep / Render / Railway / VPS.
- `package.json`: Cấu hình lệnh khởi chạy `npm start`.

## Hướng dẫn triển khai lên Botkeep Cloud
1. Chọn file nén `portfolio.zip` tại mục **03 / Source -> ZIP archive**.
2. **Lưu ý cấu hình Botkeep**:
   - Nếu triển khai dưới dạng **Node.js**: Lệnh khởi chạy `npm start` sẽ tự động gọi `node server.js` (không cần cài thêm npm packages).
   - Nếu triển khai dưới dạng **Service & website -> Static sites**: Botkeep sẽ tự nhận diện trực tiếp file `index.html`.
3. Nhấn **Deploy server**.
