# meozuhi SRT – Skin Retouch Tools cho Photoshop

© 2026 meozuhi. Bảo lưu mọi quyền. Nghiêm cấm sao chép, chỉnh sửa, phân phối lại khi chưa được phép.

Plugin retouch da, ánh sáng, màu và hiệu ứng cosplay cho Photoshop 2022 (23.3) trở lên.
Cần **key bản quyền** (gắn với máy) để dùng – liên hệ meozuhi để nhận key.

## Tải bản mới nhất

**[⬇ Tải meozuhiSRT.ccx](https://github.com/yamikara97/meozuhiSKR/raw/main/meozuhiSRT.ccx)**

Các bản cũ nằm trong thư mục [`releases/`](releases).

## Cài đặt

**Có Creative Cloud:** bấm đúp file `meozuhiSRT.ccx` → Creative Cloud hỏi cài → Đồng ý. Mở Photoshop › menu **Plugins** › **meozuhi SRT**.

**Không dùng Creative Cloud:**
1. Tắt Photoshop.
2. Đổi đuôi `meozuhiSRT.ccx` thành `meozuhiSRT.zip`, giải nén ra thư mục `meozuhiSRT` (bên trong phải thấy ngay `manifest.json`).
3. Chép thư mục đó vào thư mục Plug-ins của Photoshop:
   - Windows: `C:\Program Files\Adobe\Adobe Photoshop 2024\Plug-ins\`
   - macOS: `/Applications/Adobe Photoshop 2024/Plug-ins/`
4. Mở Photoshop › menu **Plugins** › **meozuhi SRT**.

## Cập nhật

Mỗi lần mở panel, plugin tự kiểm tra bản mới. Có bản mới thì đầu panel hiện **"Có bản mới …"** → bấm **Tải bản mới** → cài đè như trên. Key cũ vẫn dùng được (key gắn với máy, không gắn với phiên bản).

Muốn kiểm tra tay: cuối panel bấm **Kiểm tra cập nhật**.

---

## Dành cho meozuhi: phát hành bản mới

1. Đưa file `.ccx` mới lên repo này, **ghi đè** `meozuhiSRT.ccx` (và thêm 1 bản lưu vào `releases/meozuhiSRT-<phiên bản>.ccx`).
   Trên web: **Add file › Upload files** → kéo file vào → **Commit changes**.
2. Sửa `latest.json` (bấm file › biểu tượng bút chì):
   - `version`: số phiên bản mới, **phải giống** `version` trong `manifest.json` của bản đó.
   - `notes`: 1 câu ngắn về điểm mới (hiện ngay trên thông báo).
   - `minVersion`: để `1.0.0`. Chỉ khi một bản cũ có lỗi nghiêm trọng mới đặt số này = bản thấp nhất được phép dùng → bản thấp hơn sẽ **bị khoá chức năng** tới khi cập nhật.
3. **Commit changes**. Sau vài phút (GitHub lưu đệm tối đa ~5 phút), mọi người mở panel sẽ thấy thông báo.

Lưu ý: không đưa mã nguồn lên repo này (repo công khai) – chỉ file `.ccx`, `latest.json` và hướng dẫn.
