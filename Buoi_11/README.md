# Buổi 11: Singleton và Object Pooling

[Mục lục](../README.md) · [Báo cáo nội dung còn thiếu](../NOI_DUNG_CON_THIEU.md#buoi-11)

## Nội dung theo Google Sheet

-- Singleton Design Pattern
  + Vấn đề: nhiều Manager instance gây lỗi
  + Giải pháp: class Singleton generic Singleton<T> where T : MonoBehaviour
  + Đọc code Singleton.cs trong project
  + DontDestroyOnLoad — giữ object qua scene
  + Cạm bẫy: duplicate instance khi load scene
- Object Pooling Pattern
  + Vấn đề: Instantiate/Destroy mỗi frame → GC spike → giật frame
  + Giải pháp: pool — tắt/bật thay vì tạo/xoá
  + Đọc code PoolingManager.cs — static class, Dictionary<int, Pool>, Stack<GameObject>
  + PoolingManager.Spawn() và PoolingManager.Despawn()

## Tài liệu hiện có

Chưa có file tài liệu chi tiết từ repo nguồn cho buổi này. Thư mục `Tai_lieu_cu_the` được giữ bằng `.gitkeep`.

Chưa có file BTVN được chuyển từ nguồn cho buổi này. Cột BTVN trong Sheet hiện để trống; chưa xác định yêu cầu bài tập.

## Phần cần bổ sung

- Chưa có tài liệu Singleton generic, vấn đề nhiều Manager instance, DontDestroyOnLoad và xử lý duplicate instance.
- Chưa có tài liệu Object Pooling, GC spike, pool bật/tắt object và Spawn/Despawn.
- Chưa có Singleton.cs và PoolingManager.cs (Dictionary<int, Pool>, Stack<GameObject>) để đọc theo lộ trình.

Phần lộ trình và danh sách thiếu ở đây là ghi chú tổ chức mới; không phải bài giảng bổ sung.
