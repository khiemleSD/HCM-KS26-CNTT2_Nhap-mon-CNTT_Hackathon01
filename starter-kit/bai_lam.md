# BÀI LÀM – HACKATHON 01

- **Mã đề:** 16
- **Họ tên:** Lê Hoàng Anh Khiêm
- **Lớp:** CNTT 2
- **Link repository:** https://github.com/khiemleSD/HCM-KS26-CNTT2_Nhap-mon-CNTT_Hackathon01.git
- **Hệ điều hành (Windows/macOS):** windows

## 4.2. Thao tác máy tính cơ bản bằng CLI

### Các lệnh đã chạy

```shell
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng
- Get-Location
- Get-ChildItem -force
- Move-Item Quy_Dinh_Bao_Hanh.txt docs/
- Move-Item Logo_Sua_ May_Tinh.PNG media
- Remove-Item -Recurse temp_241.tmp
- cd logs
- Get-ChildItem -force

```

### Kết quả liệt kê toàn bộ dự án (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
    Directory: D:\starter-kit\sua-may-tinh-website


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/28/2026   1:42 PM                backup
d-----        10/28/2026   1:44 PM                data
d-----        10/28/2026   1:54 PM                docs
d-----        10/28/2026   1:44 PM                logs
d-----        10/28/2026   1:57 PM                media
------        10/27/2026   1:32 AM             72 .env
-a----        10/27/2026   1:32 AM           2225 bai_lam.md


    Directory: D:\starter-kit\sua-may-tinh-website\data


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/27/2026   1:32 AM           6101 Phieu_Sua_Thang_6.xlsx


    Directory: D:\starter-kit\sua-may-tinh-website\docs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/27/2026   1:32 AM             61 Quy_Dinh_Bao_Hanh.txt


    Directory: D:\starter-kit\sua-may-tinh-website\logs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/27/2026   1:32 AM           1069 Repair.log


    Directory: D:\starter-kit\sua-may-tinh-website\media


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/27/2026   1:32 AM           6767 Logo_Sua_ May_Tinh.PNG

```

## 4.3. Lọc log thủ công

### Lệnh đã chạy

```shell
# Get-Content logs/Repair.log | Select-String "ERROR"
- Get-Content logs/Repair.log | Select-Stxring "ERROR" > logs/daily_report.txt
- Get-Content logs/daily_report.txt

```

### 2 dòng lỗi đầu tiên trong daily_report.txt

```text
2026-06-28 08:57:31 [ERROR] Thanh toan bi tu choi
2026-06-28 09:01:31 [ERROR] Thanh toan bi tu choi

```

## 4.4. Thao tác với tài liệu Markdown (README.md)

> README.md được chấm trực tiếp trên file `README.md` ở gốc dự án. Đánh dấu `[x]` vào các mục đã làm để tự kiểm tra.

- [ ] Heading 1: tên dự án
- [ ] Mô tả ngắn có cả **in đậm** và *in nghiêng*
- [ ] Bảng `Thư mục | Nội dung`, ít nhất 3 dòng dữ liệu
- [ ] Code block chứa lệnh PowerShell/Terminal liệt kê nội dung dự án
- [ ] Task list ít nhất 2 công việc, có ít nhất 1 mục đã hoàn thành
- [ ] Blockquote nhắc không upload `.env`

## 4.5. Chạy script auto_report (.ps1 hoặc .sh)

### Lệnh chạy (Windows: nếu dùng Phụ lục 2 thì ghi cả 2 lệnh)

```shell
# Ghi lệnh vào đây (xoá dòng này)

```

### Kết quả hiển thị

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.6. Đếm số dòng lỗi

### Lệnh

```shell
# (Get-ChildItem daily_report.txt | select-string "ERROR").count

```

### Kết quả đếm (Windows: giá trị Count; macOS: con số in ra)

```text
6

```

## 4.7. Báo cáo tổng hợp

### Các lệnh đã chạy

```shell
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng (xoá dòng này)

```

### Nội dung file logs/tong_hop.txt

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.8. Excel

> Phần Excel được chấm trực tiếp trên file `data/phieu_sua_thang_6.xlsx`, không cần ghi vào đây.
