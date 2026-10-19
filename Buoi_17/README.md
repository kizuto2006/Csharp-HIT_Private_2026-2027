# Buổi 17: Scene Management và Menu Flow

[Mục lục](../README.md) · [Báo cáo nội dung còn thiếu](../NOI_DUNG_CON_THIEU.md#buoi-17)

## Nội dung theo Google Sheet

- Scene Management
  + SceneManager.LoadScene(name) và LoadScene(index)
  + SceneManager.LoadSceneAsync — load không đứng hình
  + AsyncOperation.progress — hiển thị loading bar
  + SceneManager.GetActiveScene().name
  + Đọc LoadScene.cs — fade out → load async → fade in bằng DOTween
- DontDestroyOnLoad
  + Mục đích: giữ object qua scene (DataManager, AudioManager, AchievementManager)
  + Cạm bẫy duplicate: cần kiểm tra instance đã tồn tại chưa (đã xử lý trong Singleton.cs)
- Menu Flow
  + IntroScene (Splash) → MenuScene → GameScene
  + Build Settings: thêm scene đúng thứ tự index
  + PlayerPrefs lưu data qua scene load

## Tài liệu hiện có

Chưa có file tài liệu chi tiết từ repo nguồn cho buổi này. Thư mục `Tai_lieu_cu_the` được giữ bằng `.gitkeep`.

Chưa có file BTVN được chuyển từ nguồn cho buổi này. Cột BTVN trong Sheet hiện để trống; chưa xác định yêu cầu bài tập.

## Phần cần bổ sung

- Chưa có bài SceneManager.LoadScene theo tên/index, LoadSceneAsync, AsyncOperation.progress và GetActiveScene().name.
- Chưa có LoadScene.cs với fade out → load async → fade in bằng DOTween.
- Chưa có thực hành DontDestroyOnLoad/duplicate instance, luồng IntroScene → MenuScene → GameScene, thứ tự scene trong Build Settings và PlayerPrefs qua scene load.

Phần lộ trình và danh sách thiếu ở đây là ghi chú tổ chức mới; không phải bài giảng bổ sung.
