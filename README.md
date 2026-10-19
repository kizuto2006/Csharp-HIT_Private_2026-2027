# C# HIT Private 2026–2027

Lộ trình được sắp xếp theo [Google Sheet](https://docs.google.com/spreadsheets/d/1my3AabWSuw7k8Oqvb2BUjIClRaJqPEOtVigYYT0cl9M/edit?gid=0#gid=0), dùng cách tổ chức học liệu theo từng buổi của [repo tham khảo](https://github.com/NguyenMinh205/C-Sharp_HIT_Private).

Đã nhập **50 file học liệu nguồn**, gồm **40 file tài liệu cụ thể**, giữ nguyên từng byte. README hướng dẫn Git ban đầu của repo này được chuyển nguyên vẹn vào [buổi 1](Buoi_1/Huong_dan_Git.md). Các file hướng dẫn tổ chức và mục lục là nội dung mới.

- [Báo cáo nội dung còn thiếu theo từng buổi](NOI_DUNG_CON_THIEU.md)
- [Bảng chuyển file và thông tin nguồn](docs/DOI_CHIEU_NGUON.md)
- [Manifest SHA-256 của các file giữ nguyên](docs/doi_chieu_nguon.json)
- [Bản chụp lộ trình từ Sheet (19/10/2026)](docs/lo_trinh_sheet.csv)

## Lộ trình và tình trạng học liệu

| Buổi | Nội dung | Tài liệu cụ thể từ nguồn | Tình trạng |
| --- | --- | ---: | --- |
| 1 | [Git, công cụ và C# nhập môn](Buoi_1/README.md) | 8 | Có tài liệu, cần bổ sung |
| 2 | [Điều kiện, vòng lặp, mảng, chuỗi và hàm](Buoi_2/README.md) | 12 | Có tài liệu, cần bổ sung |
| 3 | [Kiểu dữ liệu mở rộng và collections](Buoi_3/README.md) | 7 | Có tài liệu, cần bổ sung |
| 4 | [OOP C# cơ bản](Buoi_4/README.md) | 7 | Có tài liệu, cần bổ sung |
| 5 | [OOP nâng cao, generic, delegate, SOLID và LINQ](Buoi_5/README.md) | 6 | Có tài liệu, cần bổ sung |
| 6 | [Review OOP và làm quen Unity Editor](Buoi_6/README.md) | 0 | Chưa có bài giảng Unity |
| 7 | [GameObject, Transform và các component 2D](Buoi_7/README.md) | 0 | Chưa có bài giảng Unity |
| 8 | [Lifecycle, thời gian, input và Physics2D](Buoi_8/README.md) | 0 | Chưa có bài giảng Unity |
| 9 | [Prefab, animation và scoring](Buoi_9/README.md) | 0 | Chưa có bài giảng Unity |
| 10 | [UI và HUD](Buoi_10/README.md) | 0 | Chưa có bài giảng Unity |
| 11 | [Singleton và Object Pooling](Buoi_11/README.md) | 0 | Chưa có bài giảng Unity |
| 12 | [Coroutine, ScriptableObject và lưu dữ liệu](Buoi_12/README.md) | 0 | Chưa có bài giảng Unity |
| 13 | [DOTween, Animator nâng cao và âm thanh](Buoi_13/README.md) | 0 | Chưa có bài giảng Unity |
| 14 | [Observer và Factory](Buoi_14/README.md) | 0 | Chưa có bài giảng Unity |
| 15 | [State Machine](Buoi_15/README.md) | 0 | Chưa có bài giảng Unity |
| 16 | [Visual Effects và URP](Buoi_16/README.md) | 0 | Chưa có bài giảng Unity |
| 17 | [Scene Management và Menu Flow](Buoi_17/README.md) | 0 | Chưa có bài giảng Unity |
| 18 | [Game Loop, debug và Profiler](Buoi_18/README.md) | 0 | Chưa có bài giảng Unity |
| 19 | [Player Settings và build game](Buoi_19/README.md) | 0 | Chưa có bài giảng Unity |
| 20 | [Giải đáp và định hướng](Buoi_20/README.md) | 0 | Chưa có tài liệu giải đáp |
| 21+ | [Các buổi mở rộng (21+)](Buoi_21_plus/README.md) | 0 | Lộ trình chi tiết chưa xác định |

## Cấu trúc thư mục

```text
.
├── README.md
├── NOI_DUNG_CON_THIEU.md
├── Buoi_1/
│   ├── README.md
│   ├── Huong_dan_Git.md
│   ├── Huong_dan_Git_nguon.md
│   ├── Ly_thuyet_buoi_2_1.md
│   └── Tai_lieu_cu_the/           # 8 file nhập môn từ buổi 2 cũ
├── Buoi_2/
│   ├── README.md
│   ├── Ly_thuyet_buoi_2_2.md
│   ├── BTVN_Buoi_2.md
│   └── Tai_lieu_cu_the/           # 12 file còn lại từ buổi 2 cũ
├── Buoi_3/                       # README, lý thuyết, BTVN, 7 file chi tiết
├── Buoi_4/                       # README, lý thuyết, BTVN, 7 file chi tiết
├── Buoi_5/                       # README, lý thuyết, BTVN, 6 file chi tiết
├── Buoi_6/ ... Buoi_20/           # Mỗi buổi: README + Tai_lieu_cu_the/.gitkeep
├── Buoi_21_plus/                 # Nhóm mở rộng dự kiến theo dòng 21+ của Sheet
└── docs/
    ├── DOI_CHIEU_NGUON.md
    ├── doi_chieu_nguon.json
    └── lo_trinh_sheet.csv
```

## Cách đọc tài liệu

Mở README của từng buổi để xem nội dung theo Sheet, các file đã có, liên kết sang bài liên quan và phần còn thiếu. File gốc giữ tên và tiêu đề cũ, kể cả số buổi/số bài; vị trí thư mục và mục lục mới xác định buổi học theo lộ trình hiện tại.

Buổi 6–19 chưa có bộ bài giảng Unity từ nguồn. README của các buổi này là khung lộ trình, không phải nội dung giảng dạy đã hoàn thiện. BTVN chỉ có ở buổi 2–5; cột BTVN trong Sheet đang trống.
