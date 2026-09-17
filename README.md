# PhimHayVietSub UI

Giao diện streaming responsive theo mẫu ảnh người dùng cung cấp.

## Chạy
Mở `index.html` bằng trình duyệt hoặc dùng Live Server.

## Google Login
Trong `app.js` thay `GOOGLE_CLIENT_ID` bằng Client ID thật và triển khai backend `/api/auth/google` để xác minh ID token. Không nên tin dữ liệu role từ frontend.

## Lưu ý
Đây là frontend prototype. Tài khoản email hiện lưu LocalStorage để demo giao diện; production cần backend + database + session/cookie an toàn.
