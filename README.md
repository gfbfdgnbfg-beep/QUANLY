# Tool Manager A1 / A2 — GitHub Pages

Frontend quản lý ID + KEY cho backend Railway.

## Điểm mới

Khi tạo ID mới có thể chọn quyền:

- Tool A1
- Tool A2
- Tool A1 + A2

Trong danh sách ID có thể đổi quyền tool mà không cần đổi KEY.

## File

- `index.html` — giao diện quản lý
- `api-config.js` — URL Railway API
- `admin.html` — redirect về trang chính
- `.nojekyll` — phục vụ file tĩnh trực tiếp

## Upload GitHub Pages

Đưa toàn bộ file vào root branch `main`, sau đó:

`Settings -> Pages -> Deploy from a branch -> main -> /(root)`

Nếu Railway domain thay đổi, sửa `api-config.js`.
