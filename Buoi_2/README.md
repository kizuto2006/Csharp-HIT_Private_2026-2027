# Buổi 2: Điều kiện, vòng lặp, mảng, chuỗi và hàm

[Mục lục](../README.md) · [Báo cáo nội dung còn thiếu](../NOI_DUNG_CON_THIEU.md#buoi-2)

## Nội dung theo Google Sheet

- Vòng lặp: for, while, do-while, foreach, break, continue
- Toán tử ba ngôi (? :)
- Ép kiểu tường minh và ngầm định ((int), Convert.ToInt32)
- Cấu trúc điều kiện: if-else, switch-case
- Cách format code theo chuẩn C# (naming convention, indentation)
- Mảng (int[], string[]): khai báo, duyệt, truy cập phần tử
- Chuỗi (string): nối chuỗi, Length, Substring, Contains, Replace, ToUpper/Lower
- string interpolation ($"HP: {hp}")
- Hàm: khai báo, tham số, giá trị trả về, overload

## Tài liệu hiện có

- [BTVN_Buoi_2.md](BTVN_Buoi_2.md)
- [Ly_thuyet_buoi_2_2.md](Ly_thuyet_buoi_2_2.md)
- [9. Ép Kiểu Trong C#.txt](Tai_lieu_cu_the/9.%20%C3%89p%20Ki%E1%BB%83u%20Trong%20C%23.txt)
- [10. Cấu Trúc Lệnh Rẽ Nhánh if else Trong C#.txt](Tai_lieu_cu_the/10.%20C%E1%BA%A5u%20Tr%C3%BAc%20L%E1%BB%87nh%20R%E1%BA%BD%20Nh%C3%A1nh%20if%20else%20Trong%20C%23.txt)
- [11. Cấu Trúc switch case Trong C#.txt](Tai_lieu_cu_the/11.%20C%E1%BA%A5u%20Tr%C3%BAc%20switch%20case%20Trong%20C%23.txt)
- [12. Vòng Lặp Trong C#.txt](Tai_lieu_cu_the/12.%20V%C3%B2ng%20L%E1%BA%B7p%20Trong%20C%23.txt)
- [13. Vòng Lặp for Trong C#.txt](Tai_lieu_cu_the/13.%20V%C3%B2ng%20L%E1%BA%B7p%20for%20Trong%20C%23.txt)
- [14. Vòng Lặp while Trong C#.txt](Tai_lieu_cu_the/14.%20V%C3%B2ng%20L%E1%BA%B7p%20while%20Trong%20C%23.txt)
- [15. Vòng Lặp do while Trong C#.txt](Tai_lieu_cu_the/15.%20V%C3%B2ng%20L%E1%BA%B7p%20do%20while%20Trong%20C%23.txt)
- [16. Mảng 1 Chiều Trong C#.txt](Tai_lieu_cu_the/16.%20M%E1%BA%A3ng%201%20Chi%E1%BB%81u%20Trong%20C%23.txt)
- [17. Mảng 2 Chiều Trong C#.txt](Tai_lieu_cu_the/17.%20M%E1%BA%A3ng%202%20Chi%E1%BB%81u%20Trong%20C%23.txt)
- [18. Mảng Nhiều Chiều Trong C#.txt](Tai_lieu_cu_the/18.%20M%E1%BA%A3ng%20Nhi%E1%BB%81u%20Chi%E1%BB%81u%20Trong%20C%23.txt)
- [19. Kiểu Chuỗi String Trong C#.txt](Tai_lieu_cu_the/19.%20Ki%E1%BB%83u%20Chu%E1%BB%97i%20String%20Trong%20C%23.txt)
- [20. Cấu Trúc Hàm Cơ Bản Trong C#.txt](Tai_lieu_cu_the/20.%20C%E1%BA%A5u%20Tr%C3%BAc%20H%C3%A0m%20C%C6%A1%20B%E1%BA%A3n%20Trong%20C%23.txt)

Tên file, số thứ tự và tiêu đề bên trong tài liệu nguồn được giữ nguyên. Vì vậy file `Ly_thuyet_buoi_2_1.md` ở buổi 1 vẫn mang tiêu đề buổi 2 và còn có phần ép kiểu của buổi 2 mới.

## Tài liệu liên quan ở buổi khác

- [Toán tử ba ngôi; quy tắc đặt tên trong phần biến](../Buoi_1/Ly_thuyet_buoi_2_1.md)
- [Cú pháp và ví dụ toán tử ba ngôi](../Buoi_1/Tai_lieu_cu_the/7.%20To%C3%A1n%20T%E1%BB%AD%20Trong%20C%23.txt)
- [Ví dụ foreach và string interpolation](../Buoi_3/Ly_thuyet_buoi_3.md)
- [Overload: đọc phần nạp chồng trong file gốc](../Buoi_5/Tai_lieu_cu_the/1.%20Override%2C%20Overload%20trong%20C%23.txt)

## Phần cần bổ sung

- Chưa có phần giải thích/thực hành `continue` và dùng `break` trong vòng lặp; `break` hiện được giải thích ở switch-case.
- `foreach` được liệt kê trong tài liệu vòng lặp và có ví dụ ở buổi 3, nhưng chưa có bài giải thích riêng về cú pháp và cách duyệt mảng bằng `foreach`.
- Chưa có hướng dẫn indentation/format code theo chuẩn C#; quy tắc đặt tên đã có ở phần biến của buổi 1.
- Chưa có phần riêng về `string.Contains` và string interpolation. Các ví dụ `$"..."` hiện nằm trong tài liệu buổi 3–5; `Length`, nối chuỗi, `Substring`, `Replace`, `ToUpper/ToLower` đã có.
- Overload đã có ở tài liệu buổi 5 và được liên kết để đọc từ buổi 2; chưa có bài thực hành overload riêng gắn với phần hàm của buổi này.

Phần lộ trình và danh sách thiếu ở đây là ghi chú tổ chức mới; không phải bài giảng bổ sung.
