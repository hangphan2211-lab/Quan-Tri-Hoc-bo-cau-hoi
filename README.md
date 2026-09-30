# Quản trị học - Trắc nghiệm Chương 3–9

Website tĩnh dành cho GitHub Pages.

## Tính năng

- 7 chương (Chương 3 đến Chương 9), tổng 280 câu.
- 40 câu/chương, thời gian 30 phút.
- Bắt buộc trả lời đủ 40 câu trước khi chủ động nộp bài.
- Hết giờ tự động nộp, kể cả còn câu chưa trả lời.
- Lưu đáp án + thời điểm bắt đầu trong `localStorage`, tải lại trang không reset giờ.
- Sau khi nộp: điểm thang 10, số câu đúng/sai/chưa làm, thời gian làm bài.
- Xem lại: đáp án đúng màu xanh; nếu sinh viên chọn sai, lựa chọn sai màu đỏ và đáp án đúng màu xanh; kèm đáp án đúng, giải thích, nội dung thuộc.

## Đưa lên GitHub Pages

1. Tạo repository mới trên GitHub, ví dụ `quan-tri-hoc-quiz`.
2. Upload toàn bộ **nội dung bên trong thư mục này** lên nhánh `main`.
3. Vào **Settings → Pages**.
4. Ở **Build and deployment**, chọn **Deploy from a branch**.
5. Chọn branch `main`, thư mục `/ (root)`, bấm **Save**.
6. GitHub sẽ cung cấp đường dẫn dạng `https://TEN-TAI-KHOAN.github.io/quan-tri-hoc-quiz/`.

## Chạy thử trên máy

Có thể mở trực tiếp `index.html`. Nếu trình duyệt chặn file cục bộ, chạy một HTTP server đơn giản tại thư mục này.

## Cấu trúc

- `index.html`: trang chính / ứng dụng một trang.
- `css/style.css`: giao diện.
- `js/app.js`: logic thi, timer, chấm điểm, xem lại.
- `data/chapters.js`: toàn bộ 280 câu.
