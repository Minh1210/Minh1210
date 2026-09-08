# HƯỚNG DẪN CÀI ĐẶT GITHUB PROFILE CHO MINH1210

Chỉ cần làm theo 3 bước cực kỳ đơn giản dưới đây (khoảng 2-3 phút) là trang GitHub [github.com/Minh1210](https://github.com/Minh1210) của bạn sẽ lột xác hoàn toàn!

---

## 🚀 Bước 1: Tạo Special Repository trên GitHub

1. Truy cập [https://github.com/new](https://github.com/new).
2. Tại ô **Repository name**, nhập đúng tên username của bạn: `Minh1210`.
   > *GitHub sẽ hiện thông báo đặc biệt: "You found a secret! Minh1210/Minh1210 is a special repository that you can use to add a README.md to your GitHub profile."*
3. Chọn trạng thái **Public** *(Bắt buộc để mọi người nhìn thấy)*.
4. Đánh dấu tích vào ô **Add a README file**.
5. Nhấn **Create repository**.

---

## 🚀 Bước 2: Đưa các file vào Repository `Minh1210`

Bạn có thể dùng Git CLI hoặc trực tiếp trên giao diện web của GitHub:

### Cách 1: Dùng giao diện Web GitHub (Nhanh & Dễ nhất)
1. Trong repo `Minh1210` vừa tạo, nhấn vào nút **Add file** -> **Upload files**.
2. Kéo thả cả thư mục `assets` (chứa `banner.svg`, `snake-divider.svg`) lên repo.
3. Mở file `README.md` trong thư mục `profile-readme` này, copy toàn bộ nội dung và paste đè vào file `README.md` trên GitHub. Nhấn **Commit changes**.
4. Để kích hoạt game rắn ăn commit, tạo file `.github/workflows/snake.yml`:
   - Trên web GitHub, nhấn **Add file** -> **Create new file**.
   - Tại ô tên file, gõ: `.github/workflows/snake.yml`.
   - Copy nội dung file `snake.yml` dán vào và nhấn **Commit changes**.

### Cách 2: Dùng Git dòng lệnh (Terminal)
Chạy các lệnh sau trong thư mục `profile-readme`:
```bash
git init
git branch -M main
git remote add origin https://github.com/Minh1210/Minh1210.git
git add .
git commit -m "feat: transform github profile with mystic neon serpent aesthetic"
git push -u origin main --force
```

---

## 🚀 Bước 3: Cấp quyền cho GitHub Actions tự động chạy con rắn

Để con rắn tự động cập nhật lịch commit mà không bị chặn quyền:
1. Trong repository `Minh1210`, vào tab **Settings** -> Mục **Actions** -> Chọn **General**.
2. Kéo xuống phần **Workflow permissions**:
   - Chọn **Read and write permissions**.
   - Nhấn **Save**.
3. Vào tab **Actions** ở menu trên cùng -> Chọn workflow **Generate Snake Contribution Animation** ở cột trái -> Nhấn **Run workflow** để chạy thử ngay lần đầu tiên!

🎉 **Xong!** Bây giờ hãy mở [https://github.com/Minh1210](https://github.com/Minh1210) để chiêm ngưỡng trang cá nhân mới toanh phát sáng huyền ảo!
