# Buổi 16: Visual Effects và URP

[Mục lục](../README.md) · [Báo cáo nội dung còn thiếu](../NOI_DUNG_CON_THIEU.md#buoi-16)

## Nội dung theo Google Sheet

- Visual Effects
  + Particle System: tổng quan các module — Emission, Shape, Lifetime, Size, Color over Lifetime, Velocity
  + Tạo hiệu ứng explosion (vụ nổ), muzzle flash (lửa bắn), appear effect (khi enemy spawn)
  + Dùng PoolingManager để pool Particle System — ps.Play(), despawn sau duration + maxLifetime
  + Đọc EnemyManager.SpawnAppearEffect() và DespawnParticleAfter() Coroutine
- Universal Render Pipeline (URP)
  + So sánh Built-in vs URP: performance, tính năng
  + Cách migrate project sang URP
  + URP Asset: chỉnh Shadow, Anti-aliasing, Post Processing
  + 2D Renderer URP — phù hợp game 2D
  + Light 2D cơ bản: Global Light, Point Light

## Tài liệu hiện có

Chưa có file tài liệu chi tiết từ repo nguồn cho buổi này. Thư mục `Tai_lieu_cu_the` được giữ bằng `.gitkeep`.

Chưa có file BTVN được chuyển từ nguồn cho buổi này. Cột BTVN trong Sheet hiện để trống; chưa xác định yêu cầu bài tập.

## Phần cần bổ sung

- Chưa có tài liệu Particle System và các module Emission/Shape/Lifetime/Size/Color/Velocity.
- Chưa có thực hành explosion, muzzle flash, appear effect; pool particle, ps.Play và despawn theo duration + maxLifetime.
- Chưa có EnemyManager.SpawnAppearEffect() và Coroutine DespawnParticleAfter().
- Chưa có bài Built-in vs URP, migrate project, URP Asset (Shadow/Anti-aliasing/Post Processing), 2D Renderer và Global/Point Light 2D.

Phần lộ trình và danh sách thiếu ở đây là ghi chú tổ chức mới; không phải bài giảng bổ sung.
