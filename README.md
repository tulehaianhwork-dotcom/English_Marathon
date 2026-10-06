# IELTS Marathon — 21 Days

Ứng dụng học IELTS nhẹ, 100% frontend, xây từ bộ nội dung IELTS Marathon 21 ngày.

## Tính năng

- Daily Mission: học 1 bài + Quick Quiz + ôn flashcard.
- Focus timer 15 phút.
- 21 bài học đầy đủ từ tài liệu nguồn.
- Quick Quiz 5 câu/ngày lấy từ chính bộ từ vựng của tài liệu.
- Câu quiz sai tự động vào Error Notebook.
- Flashcard Spaced Repetition: Quên / Khó / Nhớ / Dễ.
- Streak, XP, level, achievements và trang Progress.
- Ghi chú riêng theo từng bài.
- Speaking recorder dùng microphone của trình duyệt; audio ở local và có thể tải file xuống.
- Export/import dữ liệu học dạng JSON.
- PWA/offline cache khi chạy qua HTTPS (GitHub Pages/Vercel).
- Responsive cho desktop và điện thoại.

## Chi phí

Không cần backend, database, tài khoản hay API key. Toàn bộ tiến độ lưu bằng `localStorage` trên thiết bị. Có thể deploy miễn phí trên GitHub Pages hoặc Vercel.

## Chạy ngay

Có thể mở `index.html` trực tiếp để học. Một số tính năng trình duyệt như microphone/PWA hoạt động ổn định nhất khi chạy qua HTTPS hoặc localhost.

## Deploy GitHub Pages

1. Tạo repository mới trên GitHub.
2. Upload toàn bộ file trong thư mục này vào root của repository.
3. Vào **Settings → Pages**.
4. Chọn **Deploy from a branch** → `main` → `/ (root)`.
5. Lưu và mở URL GitHub Pages được cấp.

## Deploy Vercel

Import repository GitHub vào Vercel. Đây là static site nên không cần Build Command; Output Directory để mặc định/root.

## Lưu ý dữ liệu

Vì dữ liệu nằm trên trình duyệt, mở site ở thiết bị/trình duyệt khác sẽ không tự đồng bộ. Dùng **Cài đặt → Xuất dữ liệu** để sao lưu và **Nhập dữ liệu** trên thiết bị khác.
