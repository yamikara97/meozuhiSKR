# Nhật ký thay đổi

## 1.33.0 – 2026-10-29
- Tab Chải & vẽ tóc thêm **Cọ vẽ sợi tóc**: bấm Tạo lớp vẽ sợi (layer trong suốt + cọ 3px), vẽ tay từng sợi; bấm Làm mượt sợi để nét run thành đường cong mượt, sợi thon đầu, giữ màu nét vẽ. Hỗ trợ Freeform Pen (mỗi nét một sợi). Chỉnh độ mượt nét, độ dày, độ thon, gốc sợi.

## 1.32.0 – 2026-10-29
- Tab mới **Chải & vẽ tóc** (nhóm Stock & tóc):
  - **Cà mượt & tách sợi**: khoanh vùng tóc rối / bết → tóc được chải theo dòng chảy, giữ sáng tối; chỉnh độ mượt, độ sợi, chiều dài sợi, tách sợi, hướng chải.
  - **Vẽ lọn tóc**: vẽ Pen path từ gốc ra ngọn → nét run tự làm mượt, nét thẳng tự uốn cong (C hoặc S); màu lấy từ tóc ở gốc; tách đuôi thành sợi, sợi bay.
- Tab Lọn tóc (ghép stock) đổi tên thành "Lọn tóc stock".

## 1.31.0 – 2026-10-29
- Giao diện mới: **thanh bên dạng cây** (nhóm Da & khuôn mặt / Ánh sáng & màu / Stock & tóc / Công cụ), mỗi mục có icon; bấm một mục là mở tab ngay cạnh, thanh bên đứng yên khi kéo nội dung.
- Panel hẹp (dưới ~470px) tự thu thành cột icon; nút ≡ để thu gọn / mở rộng tay (nhớ lựa chọn), bấm tên nhóm để gập.

## 1.30.0 – 2026-10-25
- Tab mới **Lọn tóc**: chọn thư mục lọn stock (nền xanh), khoanh vùng lọn cần thay (hoặc vẽ Pen path), plugin tách nền, uốn lọn theo vùng, đổi màu theo tóc, gốc tan dần vào tóc thật. Kéo thanh độ rộng / độ uốn / độ đậm / sáng / gốc tan là cập nhật.

## 1.29.0 – 2026-10-24
- Stock FX: sau khi đặt, kéo thanh kích thước / vị trí / xoay / lật là layer tự cập nhật (độ đậm và blend đổi ngay).
- Đo hướng sáng của ảnh (núm xoay chỉnh được), tự lật stock nếu ngược hướng sáng (đọc đuôi tên file _L/_R/_U/_D hoặc đo từ chính stock).
- Pha màu theo ánh sáng của ảnh; "Nằm sau nhân vật": ẩn phần trùng nhân vật bằng mask (vùng chọn có sẵn hoặc Select Subject).

## 1.28.0 – 2026-10-24
- Tab mới **Stock FX**: chọn thư mục ảnh stock trên máy (nhớ cho lần sau), lọc theo tên, xem trước, đặt vào ảnh với kích thước / vị trí / xoay / lật / độ đậm; ảnh nền đen tự dùng Screen, PNG trong suốt dùng Normal.

## 1.27.0 – 2026-10-22
- Thử nghiệm Glow Pro "Chỉnh trực tiếp": kéo thanh xem ngay trên ảnh, Lưu giữ lại (thông số nằm trong tên layer để chỉnh lại), Hủy trả về như cũ.

## 1.26.4 – 2026-10-15
- Layer và nhóm hiệu ứng mới luôn nằm ở cấp trên cùng, không chui vào nhóm khác.

## 1.26.3 – 2026-10-15
- Đọc ảnh thử nhiều kiểu (8/16-bit, có/không chỉ định không gian màu), chuyển Move tool, thử lại không dùng history khi Photoshop báo lỗi.

## 1.26.2 – 2026-10-15
- Sửa lỗi "Could not use the Patch tool" / "Could not update smart object files" trên ảnh RAW: đọc ảnh từng layer thay vì ảnh tổng hợp.

## 1.26.1 – 2026-10-15
- Ghi ảnh vào layer mới an toàn hơn trên ảnh RAW (chọn đúng layer + công cụ Move, thử nhiều cách ghi).
- Thông báo lỗi hiện rõ bước đang chạy và thông tin ảnh.

## 1.26.0 – 2026-10-15
- Sửa lỗi với ảnh RAW mở từ Camera Raw (Smart Object): "Could not open …CR3", "Could not update smart object files", "Could not make a new layer from the selection".
- Nhóm hiệu ứng luôn nằm trên mọi layer của người dùng.
- Thêm logo, biểu tượng plugin và nút "? Hướng dẫn" ở đầu mỗi tab.

## 1.25.0 – 2026-10-15
- Tự kiểm tra cập nhật khi mở panel, nút "Tải bản mới" và "Kiểm tra cập nhật".
- Núm xoay chọn hướng (Rim light, Đèn 2 bên, Glow Pro, điểm bắt sáng mắt).
- Thanh màu có dải cầu vồng, ô xem trước và nút "Hút màu" (màu cọ của Photoshop).

## 1.23.0
- Tab Ánh sáng (Rim light, Đèn 2 bên, Tia sáng, Glow anime, Lens flare), tab Màu (mức kiểu anime, tách tông, đổi dải màu, học màu từ ảnh mẫu), tab Mắt.
- Black Mist: Glow Pro kiểu Oniric (Bloom / Streaks, X-Ray, Halation, đổi màu glow).

## 1.22.0
- Tách tab Cà da tự động / Cà da thủ công / D&B.
