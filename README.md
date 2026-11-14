# Đề cương đổi mới chuyên đề AI 2026 — GitHub Pages

## Nội dung triển khai

- `index.html`: website công khai, trang mặc định của GitHub Pages.
- `fonts/Roboto-*.woff2`: font Roboto tự lưu trữ, có bộ ký tự tiếng Việt. Không phụ thuộc Google Fonts hoặc font cài trên máy người xem.
- `fonts/Roboto-LICENSE-Apache-2.0.txt`: giấy phép của Roboto.
- `.nojekyll`: bỏ qua xử lý Jekyll mặc định của GitHub Pages.

## Cách xuất bản

1. Tạo một repository trên GitHub.
2. Giải nén gói này và tải **toàn bộ nội dung bên trong** lên thư mục gốc repository. Không chỉ tải riêng `index.html`; thư mục `fonts` phải nằm cùng cấp với `index.html`.
3. Mở **Settings → Pages**.
4. Ở **Build and deployment**, chọn **Deploy from a branch**.
5. Chọn branch `main`, folder `/ (root)`, nhấn **Save**.
6. Chờ GitHub Pages triển khai, sau đó mở URL được hiển thị trong mục Pages.

## Lưu ý

- Website đã nhúng nội dung, hình ảnh và logo; font Roboto được đóng gói trong thư mục `fonts`.
- Các đường dẫn font là đường dẫn tương đối (`./fonts/...`) nên hoạt động với cả GitHub Pages dạng `username.github.io/repository/` và custom domain.
- Gói công khai này chỉ gồm bản trình bày. Bản biên tập và JSON dữ liệu được cung cấp riêng, không đưa lên repository công khai nếu không muốn công khai công cụ biên tập.
- Khi cập nhật website, thay `index.html` và giữ nguyên thư mục `fonts`.
