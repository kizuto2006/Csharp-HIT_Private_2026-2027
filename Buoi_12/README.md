# Buổi 12: Coroutine, ScriptableObject và lưu dữ liệu

[Mục lục](../README.md) · [Báo cáo nội dung còn thiếu](../NOI_DUNG_CON_THIEU.md#buoi-12)

## Nội dung theo Google Sheet

- Coroutine: IEnumerator, StartCoroutine, StopCoroutine
- yield return: WaitForSeconds, WaitForFixedUpdate, null (đợi 1 frame)
- WaitForSeconds — tránh tạo mới mỗi lần, cache lại
- ScriptableObject
  + Tại sao không hardcode số liệu trong code
  + [CreateAssetMenu] — tạo SO từ menu chuột phải
  + [System.Serializable] — hiển thị class thường trong Inspector và khi serialize
  + Đọc EnemyInfoSO.cs, WaveInfoSO.cs, RewardSO.cs
  + ScriptableObject.CreateInstance<T>() — tạo clone SO tại runtime (tránh sửa asset gốc)
- Lưu trữ dữ liệu với PlayerPrefs
  + PlayerPrefs.SetInt/GetInt, SetFloat/GetFloat, SetString/GetString
  + PlayerPrefs.Save() — khi nào gọi
  + string.Join, string.Split — serialize List thành string để lưu
  + string.IsNullOrEmpty — kiểm tra an toàn trước khi xử lý
- Đọc DataManager.cs — cách tổ chức data layer: Load/Save, #region, const default values

## Tài liệu hiện có

Chưa có file tài liệu chi tiết từ repo nguồn cho buổi này. Thư mục `Tai_lieu_cu_the` được giữ bằng `.gitkeep`.

Chưa có file BTVN được chuyển từ nguồn cho buổi này. Cột BTVN trong Sheet hiện để trống; chưa xác định yêu cầu bài tập.

## Tài liệu liên quan ở buổi khác

- [Các thao tác chuỗi đã có: Split, IsNullOrEmpty](../Buoi_2/Ly_thuyet_buoi_2_2.md)

## Phần cần bổ sung

- Chưa có tài liệu Coroutine: IEnumerator, StartCoroutine/StopCoroutine, yield return null, WaitForSeconds, WaitForFixedUpdate và cache lệnh chờ.
- Chưa có bài ScriptableObject, `[CreateAssetMenu]`, `[System.Serializable]`, CreateInstance và quản lý dữ liệu cấu hình.
- Chưa có bài PlayerPrefs Set/Get Int/Float/String, Save và thực hành serialize danh sách bằng string.Join/string.Split; Split và IsNullOrEmpty chỉ có trong tài liệu chuỗi buổi 2.
- Chưa có EnemyInfoSO.cs, WaveInfoSO.cs, RewardSO.cs và DataManager.cs.

Phần lộ trình và danh sách thiếu ở đây là ghi chú tổ chức mới; không phải bài giảng bổ sung.
