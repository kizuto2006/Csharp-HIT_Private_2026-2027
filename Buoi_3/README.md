# Buổi 3: Kiểu dữ liệu mở rộng và collections

[Mục lục](../README.md) · [Báo cáo nội dung còn thiếu](../NOI_DUNG_CON_THIEU.md#buoi-3)

## Nội dung theo Google Sheet

- Kiểu dữ liệu object, từ khoá var, dynamic
- List<T>: thêm, xoá, duyệt, truy cập, Count, Contains, Find
- Dictionary<K, V>: thêm, xoá, tra cứu, ContainsKey, TryGetValue
- Stack<T> và Queue<T>: khi nào dùng cái nào
- HashSet<T>: đặc điểm không trùng, dùng khi cần kiểm tra tồn tại nhanh
- Enum: khai báo, dùng trong switch-case
- Struct: so sánh với class, khi nào dùng
- Giới thiệu #region — cách tổ chức code gọn trong file dài

## Tài liệu hiện có

- [BTVN_Buoi_3.md](BTVN_Buoi_3.md)
- [Ly_thuyet_buoi_3.md](Ly_thuyet_buoi_3.md)
- [1. Tổng Quan Về Collection Trong C#.txt](Tai_lieu_cu_the/1.%20T%E1%BB%95ng%20Quan%20V%E1%BB%81%20Collection%20Trong%20C%23.txt)
- [2. List Trong C#.txt](Tai_lieu_cu_the/2.%20List%20Trong%20C%23.txt)
- [3. Dictionary Trong C#.txt](Tai_lieu_cu_the/3.%20Dictionary%20Trong%20C%23.txt)
- [4. Stack Trong C#.txt](Tai_lieu_cu_the/4.%20Stack%20Trong%20C%23.txt)
- [5. Queue Trong C#.txt](Tai_lieu_cu_the/5.%20Queue%20Trong%20C%23.txt)
- [6. Enum Trong C#.txt](Tai_lieu_cu_the/6.%20Enum%20Trong%20C%23.txt)
- [7. Struct Trong C#.txt](Tai_lieu_cu_the/7.%20Struct%20Trong%20C%23.txt)

Tên file, số thứ tự và tiêu đề bên trong tài liệu nguồn được giữ nguyên. Vì vậy file `Ly_thuyet_buoi_2_1.md` ở buổi 1 vẫn mang tiêu đề buổi 2 và còn có phần ép kiểu của buổi 2 mới.

## Tài liệu liên quan ở buổi khác

- [So sánh class/struct trong mục 2.5](../Buoi_4/Ly_thuyet_buoi_4.md)
- [Giới thiệu Stack<T> và Queue<T> trong phần generic](../Buoi_5/Tai_lieu_cu_the/3.%20Generic%20Trong%20C%23.txt)

## Phần cần bổ sung

- Chưa có bài giải thích và ví dụ sử dụng `object`, `var`, `dynamic`; các từ khóa này hiện chủ yếu được nhắc tên hoặc xuất hiện trong ví dụ ở buổi khác.
- Chưa có tài liệu về `HashSet<T>` và `#region`.
- Chưa có phần `List<T>.Find`; các thao tác List còn lại và `Dictionary.ContainsKey` / `TryGetValue` đã có.
- Chưa có ví dụ dùng enum trong switch-case.
- Tài liệu Stack/Queue hiện chủ yếu dùng bản không generic (`System.Collections`); cần ví dụ trực tiếp `Stack<T>` / `Queue<T>` và bài tập chọn cấu trúc theo tình huống. Generic ở buổi 5 mới giới thiệu tên các kiểu này.

Phần lộ trình và danh sách thiếu ở đây là ghi chú tổ chức mới; không phải bài giảng bổ sung.
