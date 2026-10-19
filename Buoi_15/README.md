# Buổi 15: State Machine

[Mục lục](../README.md) · [Báo cáo nội dung còn thiếu](../NOI_DUNG_CON_THIEU.md#buoi-15)

## Nội dung theo Google Sheet

- State Machine Pattern
  + Vấn đề: quản lý trạng thái bằng bool lồng nhau = spaghetti code
  + Enum-based State Machine: GameState { Playing, Paused, GameOver, ChoosingReward }
  + Chuyển state bằng switch-case, validate transition hợp lệ
  + Đọc GamePlayManager — IsGamePaused, IsChoosingReward, IsInstructionShown

## Tài liệu hiện có

Chưa có file tài liệu chi tiết từ repo nguồn cho buổi này. Thư mục `Tai_lieu_cu_the` được giữ bằng `.gitkeep`.

Chưa có file BTVN được chuyển từ nguồn cho buổi này. Cột BTVN trong Sheet hiện để trống; chưa xác định yêu cầu bài tập.

## Phần cần bổ sung

- Chưa có bài State Machine, enum GameState (Playing/Paused/GameOver/ChoosingReward), switch-case chuyển state và kiểm tra transition.
- Chưa có GamePlayManager để đọc IsGamePaused, IsChoosingReward và IsInstructionShown.

Phần lộ trình và danh sách thiếu ở đây là ghi chú tổ chức mới; không phải bài giảng bổ sung.
