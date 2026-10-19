# Nội dung còn thiếu so với lộ trình

Đối chiếu ngày 19/10/2026: [repo nguồn](https://github.com/NguyenMinh205/C-Sharp_HIT_Private) tại commit `ef7ff6384218e7b3fb1f1f2fb703debab3a8f074` và [Google Sheet, gid=0](https://docs.google.com/spreadsheets/d/1my3AabWSuw7k8Oqvb2BUjIClRaJqPEOtVigYYT0cl9M/edit?gid=0#gid=0). Bản chụp các ô của Sheet: [lo_trinh_sheet.csv](docs/lo_trinh_sheet.csv).

Nguồn có 40 file tài liệu cụ thể (.txt), 5 file tổng hợp lý thuyết, 4 file BTVN và 1 README hướng dẫn Git. Đã chuyển đủ 50 file học liệu; không nhập `.gitattributes` vì đây là cấu hình Git. README ban đầu của repo hiện tại được giữ riêng ở buổi 1.

“Chưa có” nghĩa là chưa tìm thấy bài giải thích, ví dụ hoặc mã nguồn tương ứng trong các file của repo nguồn tại commit trên. Một từ khóa xuất hiện trong danh sách hoặc đoạn code không được coi là bài học đầy đủ. File còn thiếu không được tự viết thêm nội dung giảng dạy; các thư mục mới chỉ ghi lại lộ trình và trạng thái.

Buổi 1–5 đã có học liệu nhưng chưa phủ đủ lộ trình. Buổi 6–19 chưa có bộ bài giảng Unity tương ứng; một số ví dụ C#/LINQ nhắc đến Unity không thay thế các bài này. Buổi 20 là phần giải đáp; nhóm 21+ chưa có lộ trình chi tiết.

<a id="buoi-1"></a>

## Buổi 1: Git, công cụ và C# nhập môn

[Xem đầy đủ nội dung buổi theo Sheet](Buoi_1/Muc_luc.md)

- Chưa có hướng dẫn cài đặt/thực hành Git Bash, GitHub Desktop, Fork và thiết lập JetBrains Rider / Visual Studio; tài liệu Git hiện có chủ yếu giải thích Git và lệnh Git.
- Chưa có tài liệu giới thiệu, quy ước sinh hoạt lớp và hướng dẫn dùng tài nguyên của lớp. Mục lục mới chỉ cung cấp lộ trình học.
- Cột tài liệu trong Sheet còn ghi “Link tài liệu của Leader”, “Link download Visual Studio: Link”, “Link download Rider: Link”; chưa có URL cụ thể trong các ô này.

<a id="buoi-2"></a>

## Buổi 2: Điều kiện, vòng lặp, mảng, chuỗi và hàm

[Xem đầy đủ nội dung buổi theo Sheet](Buoi_2/Muc_luc.md)

- Chưa có phần giải thích/thực hành `continue` và dùng `break` trong vòng lặp; `break` hiện được giải thích ở switch-case.
- `foreach` được liệt kê trong tài liệu vòng lặp và có ví dụ ở buổi 3, nhưng chưa có bài giải thích riêng về cú pháp và cách duyệt mảng bằng `foreach`.
- Chưa có hướng dẫn indentation/format code theo chuẩn C#; quy tắc đặt tên đã có ở phần biến của buổi 1.
- Chưa có phần riêng về `string.Contains` và string interpolation. Các ví dụ `$"..."` hiện nằm trong tài liệu buổi 3–5; `Length`, nối chuỗi, `Substring`, `Replace`, `ToUpper/ToLower` đã có.
- Overload đã có ở tài liệu buổi 5 và được liên kết để đọc từ buổi 2; chưa có bài thực hành overload riêng gắn với phần hàm của buổi này.

<a id="buoi-3"></a>

## Buổi 3: Kiểu dữ liệu mở rộng và collections

[Xem đầy đủ nội dung buổi theo Sheet](Buoi_3/Muc_luc.md)

- Chưa có bài giải thích và ví dụ sử dụng `object`, `var`, `dynamic`; các từ khóa này hiện chủ yếu được nhắc tên hoặc xuất hiện trong ví dụ ở buổi khác.
- Chưa có tài liệu về `HashSet<T>` và `#region`.
- Chưa có phần `List<T>.Find`; các thao tác List còn lại và `Dictionary.ContainsKey` / `TryGetValue` đã có.
- Chưa có ví dụ dùng enum trong switch-case.
- Tài liệu Stack/Queue hiện chủ yếu dùng bản không generic (`System.Collections`); cần ví dụ trực tiếp `Stack<T>` / `Queue<T>` và bài tập chọn cấu trúc theo tình huống. Generic ở buổi 5 mới giới thiệu tên các kiểu này.

<a id="buoi-4"></a>

## Buổi 4: OOP C# cơ bản

[Xem đầy đủ nội dung buổi theo Sheet](Buoi_4/Muc_luc.md)

- Chưa có bài giải thích cách truyền tham số `ref` / `out` cho instance method; các từ khóa này hiện xuất hiện rải rác trong ví dụ `TryParse`, struct và generic `Swap`.
- Chưa có tài liệu về null conditional `?.` và null coalescing `??`.
- `readonly` mới có bảng ngắn so sánh `const` với `static readonly`; cần ví dụ field `readonly` và cách gán trong constructor.
- Expression body đã xuất hiện ở method và getter (`get => ...`); chưa có ví dụ property rút gọn trực tiếp như `public int HP => _hp;` trong lộ trình.

<a id="buoi-5"></a>

## Buổi 5: OOP nâng cao, generic, delegate, SOLID và LINQ

[Xem đầy đủ nội dung buổi theo Sheet](Buoi_5/Muc_luc.md)

- Chưa có interface `IGetHit` và ví dụ implement lấy từ project Tank Battle.
- Chưa có Generic Constraint: `where T : class`, `where T : MonoBehaviour`, `where T : Component`.
- Chưa có bài về `event`: khai báo, subscribe/unsubscribe và phát sự kiện; tài liệu hiện giải thích delegate/multicast/callback, chỉ nhắc tên event.
- Chưa có bài về `Action<T>` / `Func<T>` và cách kết hợp lambda. Lambda đã xuất hiện trong LINQ nhưng chưa được giải thích riêng.
- SOLID đã đủ năm nguyên tắc và có ví dụ game; chưa có phần đối chiếu trực tiếp với mã nguồn Tank Battle.
- `List<T>.Find` chưa được trình bày. `Where`, `Select`, `FirstOrDefault` đã có trong tài liệu LINQ; phần ép kiểu tường minh và `as` có ở bài ép kiểu buổi 2 được liên kết sang đây.

<a id="buoi-6"></a>

## Buổi 6: Review OOP và làm quen Unity Editor

[Xem đầy đủ nội dung buổi theo Sheet](Buoi_6/Muc_luc.md)

- Chưa có đề kiểm tra OOP, đáp án/thang điểm, tài liệu sửa bài và câu hỏi review. BTVN OOP ở buổi 4–5 chỉ là tài liệu tham khảo, không thay thế đề kiểm tra.
- Chưa có tài liệu Unity Editor (Scene, Game, Project, Inspector, Hierarchy, Console), tạo GameObject, mô hình GameObject–Component và Package Manager.
- Chưa có project Tank Battle hoặc tài liệu đọc cấu trúc thư mục Assets.

<a id="buoi-7"></a>

## Buổi 7: GameObject, Transform và các component 2D

[Xem đầy đủ nội dung buổi theo Sheet](Buoi_7/Muc_luc.md)

- Chưa có tài liệu Transform (Position/Rotation/Scale), hệ tọa độ 2D và Space.World / Space.Self.
- Chưa có hướng dẫn import sprite, SpriteRenderer, Sorting Layer / Order in Layer.
- Chưa có tài liệu Rigidbody2D, Dynamic/Kinematic, Gravity Scale, Constraints, BoxCollider2D, CircleCollider2D và Collision/Trigger.
- Chưa có bài tạo/attach MonoBehaviour, `[SerializeField]`, `[Header]`, `GetComponent<T>()` và Layer.

<a id="buoi-8"></a>

## Buổi 8: Lifecycle, thời gian, input và Physics2D

[Xem đầy đủ nội dung buổi theo Sheet](Buoi_8/Muc_luc.md)

- Chưa có tài liệu chuỗi lifecycle MonoBehaviour từ Awake đến OnDestroy theo Sheet.
- Chưa có bài Time.deltaTime, chuyển động độc lập framerate và Time.timeScale.
- Chưa có bài input cũ: GetKey, GetKeyDown, GetAxis, GetMouseButton.
- Chưa có bài OnCollisionEnter2D / OnTriggerEnter2D, Physics2D.Raycast và Physics2D.OverlapCircleAll.
- Chưa có bài Quaternion.Euler, Mathf.Atan2 và Mathf.Rad2Deg.

<a id="buoi-9"></a>

## Buổi 9: Prefab, animation và scoring

[Xem đầy đủ nội dung buổi theo Sheet](Buoi_9/Muc_luc.md)

- Chưa có bài Prefab, Prefab Variant, unpack, Instantiate và Destroy có delay.
- Chưa có bài Animator Controller (state/transition/parameter), SetTrigger/SetBool/SetFloat và Animation Clip.
- Chưa có ví dụ OnDisable để unsubscribe/dọn dẹp và scoring bằng static int score.

<a id="buoi-10"></a>

## Buổi 10: UI và HUD

[Xem đầy đủ nội dung buổi theo Sheet](Buoi_10/Muc_luc.md)

- Chưa có bài Canvas (Overlay/Camera/World Space) và Rect Transform (Anchor/Pivot/Stretch).
- Chưa có bài Image/Fill Amount, Button/OnClick, Slider và TextMesh Pro/TMP Essential Resources/TMP_Text.
- Chưa có hướng dẫn Raycast Target, HUD (HP/Shield/điểm/wave) và Canvas Group fade.

<a id="buoi-11"></a>

## Buổi 11: Singleton và Object Pooling

[Xem đầy đủ nội dung buổi theo Sheet](Buoi_11/Muc_luc.md)

- Chưa có tài liệu Singleton generic, vấn đề nhiều Manager instance, DontDestroyOnLoad và xử lý duplicate instance.
- Chưa có tài liệu Object Pooling, GC spike, pool bật/tắt object và Spawn/Despawn.
- Chưa có Singleton.cs và PoolingManager.cs (Dictionary<int, Pool>, Stack<GameObject>) để đọc theo lộ trình.

<a id="buoi-12"></a>

## Buổi 12: Coroutine, ScriptableObject và lưu dữ liệu

[Xem đầy đủ nội dung buổi theo Sheet](Buoi_12/Muc_luc.md)

- Chưa có tài liệu Coroutine: IEnumerator, StartCoroutine/StopCoroutine, yield return null, WaitForSeconds, WaitForFixedUpdate và cache lệnh chờ.
- Chưa có bài ScriptableObject, `[CreateAssetMenu]`, `[System.Serializable]`, CreateInstance và quản lý dữ liệu cấu hình.
- Chưa có bài PlayerPrefs Set/Get Int/Float/String, Save và thực hành serialize danh sách bằng string.Join/string.Split; Split và IsNullOrEmpty chỉ có trong tài liệu chuỗi buổi 2.
- Chưa có EnemyInfoSO.cs, WaveInfoSO.cs, RewardSO.cs và DataManager.cs.

<a id="buoi-13"></a>

## Buổi 13: DOTween, Animator nâng cao và âm thanh

[Xem đầy đủ nội dung buổi theo Sheet](Buoi_13/Muc_luc.md)

- Chưa có tài liệu giới thiệu DOTween.
- Chưa có bài Blend Tree, Animation Event và AnimatorOverrideController.
- Chưa có bài AudioSource (PlayOneShot/clip/volume/loop), AudioListener, tách BGM/SFX và AudioManager.cs.

<a id="buoi-14"></a>

## Buổi 14: Observer và Factory

[Xem đầy đủ nội dung buổi theo Sheet](Buoi_14/Muc_luc.md)

- Chưa có bài Observer: tight coupling, Publish/Subscribe, generic static ObserverManager<T> where T : Enum và Action<object>.
- Chưa có mã nguồn/ví dụ AddRegisterEvent, PostEvent, RemoveAddListener, RemoveAllEvent và AchievementManager.cs đăng ký/hủy đăng ký sự kiện.
- Chưa có bài Factory Method, cây BarrelBase → BasicBarrel/LazerBarrel/MultipleShotBarrel/BombBarrel, abstract Fire và BarrelController.ChangeTypeOfBarrel().

<a id="buoi-15"></a>

## Buổi 15: State Machine

[Xem đầy đủ nội dung buổi theo Sheet](Buoi_15/Muc_luc.md)

- Chưa có bài State Machine, enum GameState (Playing/Paused/GameOver/ChoosingReward), switch-case chuyển state và kiểm tra transition.
- Chưa có GamePlayManager để đọc IsGamePaused, IsChoosingReward và IsInstructionShown.

<a id="buoi-16"></a>

## Buổi 16: Visual Effects và URP

[Xem đầy đủ nội dung buổi theo Sheet](Buoi_16/Muc_luc.md)

- Chưa có tài liệu Particle System và các module Emission/Shape/Lifetime/Size/Color/Velocity.
- Chưa có thực hành explosion, muzzle flash, appear effect; pool particle, ps.Play và despawn theo duration + maxLifetime.
- Chưa có EnemyManager.SpawnAppearEffect() và Coroutine DespawnParticleAfter().
- Chưa có bài Built-in vs URP, migrate project, URP Asset (Shadow/Anti-aliasing/Post Processing), 2D Renderer và Global/Point Light 2D.

<a id="buoi-17"></a>

## Buổi 17: Scene Management và Menu Flow

[Xem đầy đủ nội dung buổi theo Sheet](Buoi_17/Muc_luc.md)

- Chưa có bài SceneManager.LoadScene theo tên/index, LoadSceneAsync, AsyncOperation.progress và GetActiveScene().name.
- Chưa có LoadScene.cs với fade out → load async → fade in bằng DOTween.
- Chưa có thực hành DontDestroyOnLoad/duplicate instance, luồng IntroScene → MenuScene → GameScene, thứ tự scene trong Build Settings và PlayerPrefs qua scene load.

<a id="buoi-18"></a>

## Buổi 18: Game Loop, debug và Profiler

[Xem đầy đủ nội dung buổi theo Sheet](Buoi_18/Muc_luc.md)

- Chưa có tài liệu ghép game loop: intro/menu/game, wave/spawn/chiến đấu/phần thưởng, game over/chơi lại/về menu; chưa có toàn bộ GamePlayManager.cs.
- Chưa có bài đọc stack trace, NullReferenceException, IndexOutOfRangeException và MissingReferenceException trong Unity.
- Chưa có bài Debug.Log/LogWarning/LogError, Debug.DrawRay/DrawLine, OnDrawGizmos/OnDrawGizmosSelected.
- Chưa có thực hành pause debug bằng timeScale, breakpoint Rider/VS và Unity Profiler (CPU/memory spike).

<a id="buoi-19"></a>

## Buổi 19: Player Settings và build game

[Xem đầy đủ nội dung buổi theo Sheet](Buoi_19/Muc_luc.md)

- Chưa có bài Player Settings: tên game, Company Name, icon, Splash Screen, resolution và Fullscreen Mode.
- Chưa có bài Build Settings: thứ tự scene và Development Build.
- Chưa có hướng dẫn build Windows x64 và chạy .exe.
- Chưa có hướng dẫn module/build WebGL, compression Gzip/Brotli, memory, template và upload/embed lên itch.io.

<a id="buoi-20"></a>

## Buổi 20: Giải đáp và định hướng

[Xem đầy đủ nội dung buổi theo Sheet](Buoi_20/Muc_luc.md)

- Chưa có bộ câu hỏi/FAQ, tài liệu giải đáp và định hướng học tiếp. Đây là buổi trao đổi, Sheet không yêu cầu một bài lý thuyết cụ thể.

<a id="buoi-21"></a>

## Buổi 21+: Các buổi mở rộng (21+)

[Xem đầy đủ nội dung buổi theo Sheet](Buoi_21_plus/Muc_luc.md)

- Sheet mới ghi nhóm buổi mở rộng dự kiến 10 buổi, ưu tiên Casual/Puzzle 2D/3D; chưa có nội dung chi tiết từng buổi để đối chiếu. Repo nguồn cũng chưa có tài liệu cho nhóm này.

## Mã nguồn và tài nguyên Tank Battle còn thiếu

Không có project Unity, scene, prefab, asset hay file `.cs` nào trong repo nguồn. Những tên dưới đây được yêu cầu trong Sheet nhưng chưa có file hoặc phần triển khai để đọc:

- `IGetHit`, `Singleton.cs`, `PoolingManager.cs` và kiểu `Pool`.
- `EnemyInfoSO.cs`, `WaveInfoSO.cs`, `RewardSO.cs`, `DataManager.cs`.
- `AudioManager.cs`, `ObserverManager<T>`, `AchievementManager.cs`.
- `BarrelBase`, `BasicBarrel`, `LazerBarrel`, `MultipleShotBarrel`, `BombBarrel`, `BarrelController.ChangeTypeOfBarrel()`.
- `GamePlayManager.cs`, `EnemyManager.SpawnAppearEffect()`, `DespawnParticleAfter()` và `LoadScene.cs`.
- Các scene `IntroScene`, `MenuScene`, `GameScene`; sprite, animation, âm thanh, VFX và cấu hình URP dùng cho bài thực hành.

BTVN buổi 5 là đề xây game Console theo lượt, không phải project Unity Tank Battle. Cần project gốc hoặc tài liệu riêng để bổ sung các mục đọc code của lộ trình.

## Bài tập về nhà và kiểm tra

Chỉ có 4 file BTVN từ nguồn, ở buổi 2–5; các file này được giữ nguyên. Cột BTVN của toàn bộ Sheet đang trống, nên chưa thể xác định các bài tập bắt buộc ở những buổi còn lại. Đề kiểm tra OOP buổi 6 chưa có. Không tạo đề bài hoặc đáp án giả để lấp chỗ trống.
