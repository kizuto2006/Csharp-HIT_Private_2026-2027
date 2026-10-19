# Buổi 18: Game Loop, debug và Profiler

[Mục lục](../README.md) · [Báo cáo nội dung còn thiếu](../NOI_DUNG_CON_THIEU.md#buoi-18)

## Nội dung theo Google Sheet

- Game Loop hoàn chỉnh
+ Mở game → IntroScene → MenuScene → GameScene
+ Trong game: Start → Wave bắt đầu → Spawn enemy → Player chiến đấu → Wave kết thúc → Chọn phần thưởng → Wave tiếp theo
+ Game Over → Hiển thị kết quả → Chơi lại hoặc về Menu
+ Đọc toàn bộ GamePlayManager.cs — ghép các hệ thống lại
- Debug trong Unity
  + Đọc stack trace trên Console — tìm dòng gây lỗi
  + Exception phổ biến: NullReferenceException, IndexOutOfRangeException, MissingReferenceException
  + Debug.Log, Debug.LogWarning, Debug.LogError
  + Debug.DrawRay, Debug.DrawLine — visualize raycast trong Scene view
  + Gizmos: OnDrawGizmos, OnDrawGizmosSelected — vẽ sphere/line trong editor
  + Time.timeScale = 0 để pause debug, breakpoint trong Rider/VS
  + Unity Profiler cơ bản — xem CPU, memory spike

## Tài liệu hiện có

Chưa có file tài liệu chi tiết từ repo nguồn cho buổi này. Thư mục `Tai_lieu_cu_the` được giữ bằng `.gitkeep`.

Chưa có file BTVN được chuyển từ nguồn cho buổi này. Cột BTVN trong Sheet hiện để trống; chưa xác định yêu cầu bài tập.

## Phần cần bổ sung

- Chưa có tài liệu ghép game loop: intro/menu/game, wave/spawn/chiến đấu/phần thưởng, game over/chơi lại/về menu; chưa có toàn bộ GamePlayManager.cs.
- Chưa có bài đọc stack trace, NullReferenceException, IndexOutOfRangeException và MissingReferenceException trong Unity.
- Chưa có bài Debug.Log/LogWarning/LogError, Debug.DrawRay/DrawLine, OnDrawGizmos/OnDrawGizmosSelected.
- Chưa có thực hành pause debug bằng timeScale, breakpoint Rider/VS và Unity Profiler (CPU/memory spike).

Phần lộ trình và danh sách thiếu ở đây là ghi chú tổ chức mới; không phải bài giảng bổ sung.
