# BÀI LÀM – ÔN TẬP NGÀY 1

- **Họ tên:**
- **Lớp:**
- **Link repository:**
- **Hệ điều hành (Windows/macOS):**

## Phần A. Tổ chức thư mục bằng GUI

> Phần A được chấm qua kết quả B1 (tên thư mục gốc) và kết quả liệt kê toàn bộ dự án B8 ở Phần B, không cần ghi thêm ở đây.

## Phần B. Thao tác bằng CLI

### Các lệnh đã chạy (B1–B7)

```shell
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng
pwd
ls -Force
mv lich_hoc.txt docs
mv logo_trung_tam.PNG media
mv anh_lop_hoc.JPG media
cp media\logo_trung_tam.PNG archive
rm temp_201.tmp
rm temp_202.tmp
cd .\logs
Get-ChildItem
cd ..
cd .\docs
cp .\media\anh_lop_hoc.JPG archive
cd ..
Get-ChildItem -Force -Recurse
```

### Kết quả B1 (pwd)

```text
Path
----
C:\Users\Admin\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh>


```

### Kết quả liệt kê toàn bộ dự án – B8 (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
PS C:\Users\Admin\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh> pwd

Path
----
C:\Users\Admin\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh


PS C:\Users\Admin\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh> ls -Force


    Directory: C:\Users\Admin\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/21/2026   1:48 PM                archive
d-----        10/21/2026   1:50 PM                data
d-----        10/21/2026   1:48 PM                docs
d-----        10/21/2026   1:50 PM                logs
d-----        10/21/2026   1:48 PM                media
------        10/19/2026  10:04 AM             83 .env
-a----        10/19/2026  10:04 AM          13559 Anh_Lop_Hoc.JPG
-a----        10/19/2026  10:04 AM             67 Lich_Hoc.txt
-a----        10/19/2026  10:04 AM           5184 Logo_Trung_Tam.PNG
------        10/19/2026  10:04 AM             22 temp_201.tmp
------        10/19/2026  10:04 AM             22 temp_202.tmp


PS C:\Users\Admin\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh> mv lich_hoc.txt docs
PS C:\Users\Admin\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh> mv logo_trung_tam.PNG media
PS C:\Users\Admin\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh> mv anh_lop_hoc.JPG media
PS C:\Users\Admin\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh> cp media\logo_trung_tam.PNG archive
PS C:\Users\Admin\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh> rm temp_201.tmp
PS C:\Users\Admin\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh> rm temp_202.tmp
PS C:\Users\Admin\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh> cd .\logs
PS C:\Users\Admin\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh\logs> Get-ChildItem


    Directory: C:\Users\Admin\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh\logs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/19/2026  10:04 AM           1072 Access.log


PS C:\Users\Admin\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh\logs> cd ..
PS C:\Users\Admin\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh> cd .\docs
PS C:\Users\Admin\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh\docs> cp .\media\anh_lop_hoc.JPG
PS C:\Users\Admin\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh> cp ".\media\anh_lop_hoc.JPG" .\archive
PS C:\Users\Admin\Downloads\starter-kit\starter-kit\trung-tam-tieng-anh> cd ..

```

## Tự chấm (điền sau khi có đáp án)

- **Điểm tự chấm:** ..../100
- **Lỗi mình đã mắc và cách sửa:**
