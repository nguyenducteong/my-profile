# Sh1zuku Personal Website

Đây là một website tĩnh đơn giản để giới thiệu thông tin cá nhân và mạng xã hội.

## Cách dùng
1. Mở `index.html` trong trình duyệt để xem giao diện.
2. Thay thế các đường dẫn Facebook, Instagram, TikTok bằng thông tin cá nhân của bạn.

## Triển khai lên GitHub Pages
1. Tạo một repository GitHub mới.
2. Đưa toàn bộ nội dung thư mục `sh1zuku-personal-site` lên repository đó.
3. Vào `Settings` -> `Pages`, chọn nguồn `main` hoặc `master`, sau đó lưu.
4. GitHub Pages sẽ cung cấp URL để mọi người truy cập.

## Thiết lập Custom Domain (teongprofile.com)
1. Mua domain `teongprofile.com` từ Namecheap hoặc GoDaddy.
2. Cấu hình DNS: Thêm 4 records A trỏ tới GitHub IPs (185.199.108.153, etc.) và CNAME cho www.
3. Vào repository `Settings` -> `Pages` -> nhập `teongprofile.com` vào Custom domain.
4. Đợi 24-48 giờ để DNS cập nhật.

## Domain miễn phí với Freenom
1. Vào `https://www.freenom.com/`.
2. Tìm `teongprofile` và chọn một tên miễn phí còn trống như `teongprofile.tk`, `teongprofile.ml`, `teongprofile.ga`, `teongprofile.cf` hoặc `teongprofile.gq`.
3. Đăng ký tài khoản Freenom và hoàn tất đặt miễn phí.
4. Trong quản lý DNS Freenom, thêm 4 record A cho `@`:
   - 185.199.108.153
   - 185.199.109.153
   - 185.199.110.153
   - 185.199.111.153
5. Thêm record CNAME cho `www` trỏ tới `nguyenducteong.github.io`.
6. Vào repo `Settings` -> `Pages`, nhập domain miễn phí bạn đã đăng ký, ví dụ `teongprofile.tk`.
7. Đợi vài phút đến vài giờ để DNS cập nhật.

## Đã chuẩn bị xong
- Website đã có đầy đủ `index.html` và `styles.css`.
- Repository Git đã được khởi tạo trong thư mục này.
- File `CNAME` đã được cập nhật sẵn thành `teongprofile.tk`.

> Lưu ý: bạn cần tự đăng ký `teongprofile.tk` trên Freenom và cấu hình DNS rồi GitHub Pages mới hoạt động.
- File CNAME đã được thêm cho custom domain.

### Nếu bạn dùng Git lần đầu
```powershell
cd "C:\Users\mochi\Desktop\sh1zuku-personal-site"
git add .
git commit -m "Initial website setup"
git remote add origin <URL-repo-cua-ban>
git push -u origin main
```

> Thay `<URL-repo-cua-ban>` bằng đường dẫn repository GitHub của bạn. Sau khi đẩy lên, bật GitHub Pages để website truy cập được.
