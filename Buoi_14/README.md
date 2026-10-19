# Buổi 14: Observer và Factory

[Mục lục](../README.md) · [Báo cáo nội dung còn thiếu](../NOI_DUNG_CON_THIEU.md#buoi-14)

## Nội dung theo Google Sheet

- Observer Pattern
  + Vấn đề: tight coupling — GamePlayManager gọi thẳng UIController, AchievementManager...
  + Giải pháp: Publish/Subscribe — ai cần thì đăng ký, không cần biết nhau
  + Đọc ObserverManager<T> where T : Enum — generic static class
  + AddRegisterEvent, PostEvent, RemoveAddListener, RemoveAllEvent
  + Tại sao dùng Action<object> thay vì Action<T> cụ thể
  + Đọc AchievementManager.cs — subscribe trong Awake, unsubscribe trong OnDisable
- Factory Pattern
  + Vấn đề: if-else dài để tạo nhiều loại object giống nhau
  + Giải pháp: Factory Method — định nghĩa interface, lớp con quyết định tạo gì
  + Đọc BarrelBase (abstract) → BasicBarrel, LazerBarrel, MultipleShotBarrel, BombBarrel
  + abstract void Fire() — lớp con tự implement cách bắn
  + BarrelController.ChangeTypeOfBarrel() — đổi barrel runtime

## Tài liệu hiện có

Chưa có file tài liệu chi tiết từ repo nguồn cho buổi này. Thư mục `Tai_lieu_cu_the` được giữ bằng `.gitkeep`.

Chưa có file BTVN được chuyển từ nguồn cho buổi này. Cột BTVN trong Sheet hiện để trống; chưa xác định yêu cầu bài tập.

## Phần cần bổ sung

- Chưa có bài Observer: tight coupling, Publish/Subscribe, generic static ObserverManager<T> where T : Enum và Action<object>.
- Chưa có mã nguồn/ví dụ AddRegisterEvent, PostEvent, RemoveAddListener, RemoveAllEvent và AchievementManager.cs đăng ký/hủy đăng ký sự kiện.
- Chưa có bài Factory Method, cây BarrelBase → BasicBarrel/LazerBarrel/MultipleShotBarrel/BombBarrel, abstract Fire và BarrelController.ChangeTypeOfBarrel().

Phần lộ trình và danh sách thiếu ở đây là ghi chú tổ chức mới; không phải bài giảng bổ sung.
