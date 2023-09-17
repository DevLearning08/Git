# Git căn bản

# 1. Config name và email cho git với `git config`

- Git có 2 loại config là `local` và `global`. Local là dành riêng cho dự án, Global là cho cả máy tính, nếu không config thì Git sẽ tự động dùng config của global.

- Để xem các config ở local

```bash
git config --local --list
```

- Để xem các config ở global

```bash
git config --global --list
```

# 2. Tạo repository

- Để tạo 1 kho lưu trữ sourcode trên git ta dùng lệnh:

```bash
git init
```

# 3. Clone hay sao chép 1 repository từ Git

- Sử dụng để sao chép 1 repository từ Git

```bash
git clone <URL>
```

# 4. Cập nhật thông tin sourcode

- Sử dụng để cập nhật sourcode từ git về máy tính

```bash
git pull
```

# 5. Thêm các thư mục hoặc file vào repository

- Sử dụng để thêm các tệp, thư mục cụ thể được chỉ định

```bash
git add <tên thư mục hoặc tên file>
```

- Sử dụng để thêm tất cả các tệp và thư mục

```bash
git add .
```

# 6. Mô tả thông tin tệp hoặc file từ lệnh `git add`

- Sử dụng để mô tả thông tin cho thư mục hoặc tệp được thêm mới hoặc cập nhật.

```bash
git commit --m 'nội dung mô tả'
```

# 7. Sử dụng để đẩy code từ máy tính lên Git

- Sử dụng để đẩy sourcecode từ máy tính lên github

```bash
git push
```

# 8. Hiển thị các mô tả hay các `commit`

- Sử dụng để hiện thị các `commit` trên nhánh hiện tại.

```bash
git log
```
