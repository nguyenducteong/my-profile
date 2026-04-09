# Sh1zuku Personal Website

Đây là một website tĩnh đơn giản để giới thiệu thông tin cá nhân và mạng xã hội.

## Cách dùng
1. Mở `index.html` trong trình duyệt để xem giao diện.
2. Thay thế các đường dẫn Facebook, Instagram, TikTok bằng thông tin cá nhân của bạn.

## Triển khai lên GitHub Pages
1. Đã đẩy website lên GitHub repository `nguyenducteong/my-profile`.
2. Website đang hoạt động qua URL:
   - `https://nguyenducteong.github.io/my-profile`
3. Nếu bạn không muốn dùng custom domain, cứ dùng URL trên để chia sẻ.

## Tùy chọn custom domain
- Nếu bạn mua hoặc đăng ký domain, bạn có thể cấu hình cho GitHub Pages.
- Hiện tại site đã sẵn sàng nếu bạn đăng ký một domain miễn phí hoặc trả phí và cập nhật DNS đúng.

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
- File `CNAME` đã được chuyển về mặc định để GitHub Pages hoạt động với URL GitHub Pages.

> Nếu bạn muốn tôi giúp tiếp, hãy gửi tên domain bạn đã đăng ký hoặc nếu bạn cần tôi hướng dẫn mua domain rẻ từ Namecheap/Porkbun.

### Nếu bạn dùng Git lần đầu
```powershell
cd "C:\Users\mochi\Desktop\sh1zuku-personal-site"
git add .
git commit -m "Initial website setup"
git remote add origin <URL-repo-cua-ban>
git push -u origin main
```

> Thay `<URL-repo-cua-ban>` bằng đường dẫn repository GitHub của bạn. Sau khi đẩy lên, bật GitHub Pages để website truy cập được.
