# Buổi 5: OOP nâng cao, generic, delegate, SOLID và LINQ

[Mục lục](../README.md) · [Báo cáo nội dung còn thiếu](../NOI_DUNG_CON_THIEU.md#buoi-5)

## Nội dung theo Google Sheet

- Interface: khai báo, implement, tại sao không dùng class
- IGetHit — viết interface 1 method như trong project
- override vs overload — phân biệt rõ
- Generic <T>: viết method generic, đọc List<T> hiểu hơn
- Generic Constraint: where T : class, where T : MonoBehaviour, where T : Component
- delegate và event: khai báo, subscribe, invoke
- Action<T>, Func<T>: lambda expression cơ bản
- as casting vs (Type) casting — khi nào dùng cái nào
- Nguyên tắc SOLID — 5 nguyên tắc, ví dụ thực tế từ Tank Battle
- Giới thiệu Linq: Where, Select, Find, FirstOrDefault (đọc hiểu, không bắt buộc nhớ)

## Tài liệu hiện có

- [BTVN_Buoi_5.md](BTVN_Buoi_5.md)
- [Ly_thuyet_buoi_5.md](Ly_thuyet_buoi_5.md)
- [1. Override, Overload trong C#.txt](Tai_lieu_cu_the/1.%20Override%2C%20Overload%20trong%20C%23.txt)
- [2. Interface Trong OOP C#.txt](Tai_lieu_cu_the/2.%20Interface%20Trong%20OOP%20C%23.txt)
- [3. Generic Trong C#.txt](Tai_lieu_cu_the/3.%20Generic%20Trong%20C%23.txt)
- [4. Delegate Trong C#.txt](Tai_lieu_cu_the/4.%20Delegate%20Trong%20C%23.txt)
- [5. Quy tắc SOLID.txt](Tai_lieu_cu_the/5.%20Quy%20t%E1%BA%AFc%20SOLID.txt)
- [6. Giới thiệu về Linq trong C#.txt](Tai_lieu_cu_the/6.%20Gi%E1%BB%9Bi%20thi%E1%BB%87u%20v%E1%BB%81%20Linq%20trong%20C%23.txt)

Tên file, số thứ tự và tiêu đề bên trong tài liệu nguồn được giữ nguyên. Vì vậy file `Ly_thuyet_buoi_2_1.md` ở buổi 1 vẫn mang tiêu đề buổi 2 và còn có phần ép kiểu của buổi 2 mới.

## Tài liệu liên quan ở buổi khác

- [Ép kiểu tường minh và as](../Buoi_2/Tai_lieu_cu_the/9.%20%C3%89p%20Ki%E1%BB%83u%20Trong%20C%23.txt)

## Phần cần bổ sung

- Chưa có interface `IGetHit` và ví dụ implement lấy từ project Tank Battle.
- Chưa có Generic Constraint: `where T : class`, `where T : MonoBehaviour`, `where T : Component`.
- Chưa có bài về `event`: khai báo, subscribe/unsubscribe và phát sự kiện; tài liệu hiện giải thích delegate/multicast/callback, chỉ nhắc tên event.
- Chưa có bài về `Action<T>` / `Func<T>` và cách kết hợp lambda. Lambda đã xuất hiện trong LINQ nhưng chưa được giải thích riêng.
- SOLID đã đủ năm nguyên tắc và có ví dụ game; chưa có phần đối chiếu trực tiếp với mã nguồn Tank Battle.
- `List<T>.Find` chưa được trình bày. `Where`, `Select`, `FirstOrDefault` đã có trong tài liệu LINQ; phần ép kiểu tường minh và `as` có ở bài ép kiểu buổi 2 được liên kết sang đây.

Phần lộ trình và danh sách thiếu ở đây là ghi chú tổ chức mới; không phải bài giảng bổ sung.
