# Terms of Use & Privacy Policy

Trang web đơn giản chứa Terms of Use và Privacy Policy cho ứng dụng của bạn.

## Cấu trúc

- `index.html` - Trang chủ với liên kết đến các tài liệu
- `terms-of-use.html` - Điều khoản sử dụng
- `privacy-policy.html` - Chính sách bảo mật

## Cách publish lên GitHub Pages

### Bước 1: Tạo repository trên GitHub

1. Tạo một repository mới trên GitHub (ví dụ: `tos-privacy`)
2. Clone repository về máy:
```bash
git clone https://github.com/username/tos-privacy.git
cd tos-privacy
```

### Bước 2: Copy các file HTML vào repository

Copy tất cả các file HTML vào thư mục repository.

### Bước 3: Push lên GitHub

```bash
git add .
git commit -m "Add Terms of Use and Privacy Policy"
git push origin main
```

### Bước 4: Bật GitHub Pages

1. Vào Settings của repository trên GitHub
2. Scroll xuống phần "Pages" ở sidebar bên trái
3. Trong "Source", chọn branch `main` (hoặc `master`)
4. Chọn folder `/ (root)`
5. Click "Save"

### Bước 5: Truy cập trang web

Sau vài phút, trang web của bạn sẽ có sẵn tại:
```
https://username.github.io/tos-privacy/
```

## Tùy chỉnh

Bạn có thể chỉnh sửa nội dung trong các file HTML để phù hợp với ứng dụng của mình:
- Thay đổi thông tin liên hệ
- Thêm hoặc xóa các điều khoản
- Cập nhật màu sắc và style trong thẻ `<style>`

## Lưu ý

- Nhớ cập nhật thông tin liên hệ trong cả hai file
- Đảm bảo nội dung phù hợp với luật pháp địa phương
- Có thể cần tham khảo ý kiến pháp lý cho các ứng dụng thương mại

