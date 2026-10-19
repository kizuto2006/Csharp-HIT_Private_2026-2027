# Buổi 8: Lifecycle, thời gian, input và Physics2D

[Mục lục](../README.md) · [Báo cáo nội dung còn thiếu](../NOI_DUNG_CON_THIEU.md#buoi-8)

## Nội dung theo Google Sheet

- MonoBehaviour lifecycle đầy đủ: Awake → OnEnable → Start → Update → FixedUpdate → LateUpdate → OnApplicationQuit → OnDisable → OnDestroy
- Time.deltaTime — tại sao cần, framerate-independent movement
- Time.timeScale — pause/resume game
- Input cũ: Input.GetKey, Input.GetKeyDown, Input.GetAxis, Input.GetMouseButton
- OnCollisionEnter2D vs OnTriggerEnter2D — khi nào gọi, truyền tham số gì
- Physics2D.Raycast — bắn tia, phát hiện vật cản
- Physics2D.OverlapCircleAll — phát hiện vật trong vùng tròn
- Quaternion.Euler(0, 0, angle) — xoay theo góc Z
- Mathf.Atan2, Mathf.Rad2Deg — tính góc từ vector

## Tài liệu hiện có

Chưa có file tài liệu chi tiết từ repo nguồn cho buổi này. Thư mục `Tai_lieu_cu_the` được giữ bằng `.gitkeep`.

Chưa có file BTVN được chuyển từ nguồn cho buổi này. Cột BTVN trong Sheet hiện để trống; chưa xác định yêu cầu bài tập.

## Phần cần bổ sung

- Chưa có tài liệu chuỗi lifecycle MonoBehaviour từ Awake đến OnDestroy theo Sheet.
- Chưa có bài Time.deltaTime, chuyển động độc lập framerate và Time.timeScale.
- Chưa có bài input cũ: GetKey, GetKeyDown, GetAxis, GetMouseButton.
- Chưa có bài OnCollisionEnter2D / OnTriggerEnter2D, Physics2D.Raycast và Physics2D.OverlapCircleAll.
- Chưa có bài Quaternion.Euler, Mathf.Atan2 và Mathf.Rad2Deg.

Phần lộ trình và danh sách thiếu ở đây là ghi chú tổ chức mới; không phải bài giảng bổ sung.
