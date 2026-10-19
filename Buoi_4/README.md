# Buổi 4: OOP C# cơ bản

[Mục lục](../README.md) · [Báo cáo nội dung còn thiếu](../NOI_DUNG_CON_THIEU.md#buoi-4)

## Nội dung theo Google Sheet

- OOP C# và các tính chất: Encapsulation, Inheritance, Polymorphism, Abstraction
- Class và đối tượng: khai báo, new, constructor
- Thuộc tính: field private + property { get; set; } vs { get => ...; }
- Phương thức: instance method, tham số ref/out
- Từ khoá static: biến tĩnh, phương thức tĩnh, static class
- Phạm vi truy cập: public, private, protected, internal
- Con trỏ this
- Từ khoá virtual, abstract, override
- Kế thừa: lớp cha → lớp con, base.Method()
- readonly: khác const ở điểm nào
- Cú pháp ?. (null conditional), ?? (null coalescing)
- Expression body: public int HP => _hp;

## Tài liệu hiện có

- [BTVN_Buoi_4.md](BTVN_Buoi_4.md)
- [Ly_thuyet_buoi_4.md](Ly_thuyet_buoi_4.md)
- [1. Tổng Quan Về Lập Trình Hướng Đối Tượng.txt](Tai_lieu_cu_the/1.%20T%E1%BB%95ng%20Quan%20V%E1%BB%81%20L%E1%BA%ADp%20Tr%C3%ACnh%20H%C6%B0%E1%BB%9Bng%20%C4%90%E1%BB%91i%20T%C6%B0%E1%BB%A3ng.txt)
- [2. Class Trong C#.txt](Tai_lieu_cu_the/2.%20Class%20Trong%20C%23.txt)
- [3. Các Loại Phạm Vi Truy Cập Trong C#.txt](Tai_lieu_cu_the/3.%20C%C3%A1c%20Lo%E1%BA%A1i%20Ph%E1%BA%A1m%20Vi%20Truy%20C%E1%BA%ADp%20Trong%20C%23.txt)
- [4. Kế Thừa Trong OOP C#.txt](Tai_lieu_cu_the/4.%20K%E1%BA%BF%20Th%E1%BB%ABa%20Trong%20OOP%20C%23.txt)
- [5. Tính Đa Hình Trong OOP C#.txt](Tai_lieu_cu_the/5.%20T%C3%ADnh%20%C4%90a%20H%C3%ACnh%20Trong%20OOP%20C%23.txt)
- [6. Từ Khoá Static Trong C#.txt](Tai_lieu_cu_the/6.%20T%E1%BB%AB%20Kho%C3%A1%20Static%20Trong%20C%23.txt)
- [7. Từ Khóa This Trong C#.txt](Tai_lieu_cu_the/7.%20T%E1%BB%AB%20Kh%C3%B3a%20This%20Trong%20C%23.txt)

Tên file, số thứ tự và tiêu đề bên trong tài liệu nguồn được giữ nguyên. Vì vậy file `Ly_thuyet_buoi_2_1.md` ở buổi 1 vẫn mang tiêu đề buổi 2 và còn có phần ép kiểu của buổi 2 mới.

## Tài liệu liên quan ở buổi khác

- [Ví dụ ref trong generic Swap; chưa thay thế bài ref/out](../Buoi_5/Tai_lieu_cu_the/3.%20Generic%20Trong%20C%23.txt)
- [Ví dụ out và ép kiểu](../Buoi_2/Tai_lieu_cu_the/9.%20%C3%89p%20Ki%E1%BB%83u%20Trong%20C%23.txt)

## Phần cần bổ sung

- Chưa có bài giải thích cách truyền tham số `ref` / `out` cho instance method; các từ khóa này hiện xuất hiện rải rác trong ví dụ `TryParse`, struct và generic `Swap`.
- Chưa có tài liệu về null conditional `?.` và null coalescing `??`.
- `readonly` mới có bảng ngắn so sánh `const` với `static readonly`; cần ví dụ field `readonly` và cách gán trong constructor.
- Expression body đã xuất hiện ở method và getter (`get => ...`); chưa có ví dụ property rút gọn trực tiếp như `public int HP => _hp;` trong lộ trình.

Phần lộ trình và danh sách thiếu ở đây là ghi chú tổ chức mới; không phải bài giảng bổ sung.
