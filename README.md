# 📚 PrintListBook - Quản Lý, Nhập Excel & In Phiếu Đăng Ký Sách Chuẩn A4 / 2xA5 (Lớp 1 - 12)

Ứng dụng web tĩnh (Single file HTML) chuyên dụng để tạo, quản lý và in **"Phiếu đăng kí mua sách và các sản phẩm giáo dục"** theo chuẩn hành chính trường học Việt Nam cho **đầy đủ 12 khối lớp (từ Lớp 1 đến Lớp 12)**.

Ứng dụng chạy 100% trên trình duyệt (client-side), **không cần backend, không cần database server**, sẵn sàng deploy trực tiếp lên **GitHub Pages**.

---

## 🌟 Các Tính Năng Nổi Bật Mới Nhất

### 1. 📋 Đầy Đủ 12 Khối Lớp (Lớp 1 đến Lớp 12)
- Danh sách 12 khối lớp được bố trí ở **thanh bên trái** gọn gàng, trực quan.
- Mỗi khối lớp đã được nạp sẵn danh mục sách giáo khoa chuẩn theo chương trình GDPT của Bộ Giáo dục & Đào tạo với đầy đủ đơn giá.
- Bấm vào lớp nào là chuyển ngay sang phiếu của lớp đó.

### 2. ⭐ Mẫu Chuẩn Riêng Biệt Cho Từng Lớp (1 Đến 12)
- Mỗi lớp có bộ nhớ mẫu chuẩn độc lập:
  - **`⭐ Lưu Mẫu Chuẩn Lớp Này`**: Lưu lại bảng sách, thông tin trường và giá của lớp đang chọn làm mẫu chuẩn riêng của lớp đó.
  - **`🔄 Về Mẫu Chuẩn Lớp Này`**: Nếu trong quá trình sử dụng lỡ nhập sai số lượng, xóa nhầm dòng sách hoặc muốn hoàn tác, chỉ cần bấm nút này để lớp đó lập tức trở về mẫu chuẩn đã lưu.

### 3. 📄📄 Chế Độ In 2 Phiếu A5 Trên 1 Trang A4 (Tiết Kiệm 50% Giấy & Luôn Khít Đúng 1 Trang)
- Cho phép chọn giữa 2 chế độ:
  - **Khổ A4 đơn**: In 1 phiếu lớn trên 1 tờ A4 đứng.
  - **Khổ A5 tiết kiệm**: Tự động nhân đôi thành **2 phiếu A5 nằm cạnh nhau trên 1 tờ A4 ngang**, ở giữa có đường kẻ đứt nét phân cách chuẩn để cắt đôi gọn gàng.
- **Tối ưu in ấn 100% không tràn sang trang thứ 2**: Chiều cao các hàng, tiêu đề, khoảng cách ký tên được căn chỉnh theo chuẩn biểu mẫu hành chính thu nhỏ (font 8pt, đệm ký 20px). Khi bấm In phiếu / Lưu PDF, toàn bộ biểu mẫu nằm trọn vẹn trong **đúng 1 tờ giấy duy nhất**, không bao giờ bị tách rời phần chữ ký sang trang 2.

### 4. 🔀 Ghép Xen Kẽ Các Khối Lớp Trên Khổ A5 (Nút Ngay Cụm Thu Phóng)
- **Nút `🔀 Ghép xen kẽ lớp`** được bố trí ngay trên thanh công cụ nổi (cạnh cụm nút Thu Phóng và Lưu/Khôi phục Mẫu Chuẩn).
- **In 2 lớp khác nhau trên cùng 1 trang**: Bạn có thể chọn nửa bên Trái là Lớp 1, nửa bên Phải là Lớp 2 (hoặc bất kỳ cặp lớp nào từ Lớp 1 đến 12). Cắt đôi tờ giấy sẽ có ngay phiếu của 2 lớp khác nhau.
- **Tự động chuyển về dạng A5**: Ngay khi bấm "Áp dụng ghép", hệ thống sẽ tự động kích hoạt chế độ in Khổ A5 đôi (`a5-double`) mà không cần phải vào menu cài đặt thủ công.
- **Bộ phím tắt chọn nhanh tiện lợi**: Cung cấp sẵn các nút ghép cặp phổ biến (`1 + 2`, `3 + 4`, `5 + 6`, `7 + 8`, `9 + 10`, `11 + 12`, hoặc `Nhân đôi cùng lớp`), cùng nút **`⇄` Đổi bên Trái / Phải** nhanh chóng.
- **Chỉnh sửa độc lập**: Cả 2 phiếu nửa Trái và nửa Phải đều hiển thị đúng tên sách, đơn giá của từng lớp tương ứng và cho phép chỉnh sửa trực tiếp.

### 5. 🎛️ Bảng Tùy Chọn Bản In Đặt Bên Phải (Cố Định & Có Thể Ẩn/Hiện)
- Toàn bộ tùy chọn in ấn (khổ in A4/A5, cách đánh số STT, chế độ in phiếu trắng/số lượng, bật tắt chữ ký, cột thành tiền, thống kê) được đưa sang **thanh bên phải**.
- Nút **`⚙️ Tùy chọn in`** trên thanh tiêu đề và nút `✕` cho phép bạn ẩn/hiện thanh này bất cứ lúc nào để không gian xem trước phiếu rộng rãi nhất.

### 6. 📌 2 Thanh Bên Cố Định & Di Chuyển Trang A4 Linh Hoạt (Canvas Panning)
- **2 thanh bên (Danh sách 12 khối lớp & Tùy chọn in) được cố định 100%**: Không bị cuộn trôi hay rung giật khi tương tác.
- **Di chuyển trang A4 tự do**: Bạn có thể bấm giữ chuột trên nền xám và kéo rê chuột để di chuyển (pan) trang A4 theo mọi hướng, hoặc lăn con lăn chuột để cuộn lên/xuống mượt mà.
- **Tiêu chuẩn cột hành chính**: Cột đã được đổi tên thành **`SỐ LƯỢNG`** và xóa sạch mọi chữ thừa (như nhãn cắt đôi hay nút thừa giữa bảng) để giữ mẫu in chuẩn mực nhất.

### 7. 💰 Gom Tổng Tiền & Đơn Vị Vào 1 Ô Gọn Gàng
- Dòng tổng cộng số tiền được gộp thống nhất vào 1 ô căn phải: `... đồng`, không còn bị tách rời chữ "đồng" sang ô riêng.

### 8. 📊 Nhập Danh Mục Từ File Excel
- Nút **"Nhập Excel"** trên thanh tiêu đề hỗ trợ tải file `.xlsx`, `.xls`, `.csv` để nạp tự động danh mục sách và đơn giá vào lớp đang chọn.

### 9. ↔️ Thanh Bên Trái Co Giãn Tự Động Phóng To / Thu Nhỏ Chữ
- **Kéo dãn linh hoạt**: Bạn có thể di chuột đến mép phải của thanh danh sách 12 khối lớp (con trỏ chuột sẽ đổi thành dạng mũi tên hai chiều `↔`) và kéo sang phải để mở rộng hoặc kéo sang trái để thu gọn.
- **Tự động đổi cỡ chữ (Dynamic Font Scaling)**:
  - Khi kéo rộng ra (hướng vào giữa màn hình): Chữ tên lớp, số lượng sách và tiêu đề sẽ **tự động phóng to ra và đậm nét hơn**, giúp nhìn rõ ràng trên màn hình lớn.
  - Khi kéo hẹp lại: Chữ và badge sẽ tự động thu nhỏ lại gọn gàng, không bị tràn hay rớt dòng.
- **Nhấp đúp chuột để đặt lại**: Nhấp đúp chuột (Double click) vào đường chia mép phải để thanh trở về kích thước mặc định (`210px`).
- **Tự động lưu**: Kích thước và cỡ chữ tùy chỉnh được lưu tự động trong trình duyệt (`localStorage`).

### 10. 📏 Cây Thước Đo Chiều Cao & Vạch Cảnh Báo Tràn Khung A4 (Chống In Tràn Sang Tờ 2)
- **Cây thước đo chuẩn cm/mm (Vertical Ruler)**: Được bố trí chạy dọc theo cạnh trái của tờ giấy A4, có vạch chia milimet và số centimet chi tiết (`0, 1, 2, ... 21cm ... 29.7cm`).
- **Vạch giới hạn A4 màu đỏ (GIỚI HẠN)**: Hiển thị mốc chuẩn `21.0cm` (đối với khổ A4 ngang / 2xA5) hoặc `29.7cm` (đối với khổ A4 đứng).
- **Vạch cảnh báo tràn trang trực quan**: Khi danh mục sách dài làm nội dung vượt quá chiều cao trang A4 (khiến khi in bị đẩy sang tờ thứ 2):
  - Một **đường viền đỏ đứt nét** sẽ cắt ngang trang giấy tại đúng vị trí ngắt trang: `⚠️ GIỚI HẠN 1 TRANG A4 (Đã tràn +...mm sang trang 2)`.
  - Trên thanh công cụ và trên vạch đỏ có nút **`⚡ Co vừa 1 trang`**.
- **Tính năng 1-click `⚡ Co vừa 1 trang` (Auto-fit to 1 Page)**: Tự động tối ưu nhẹ khoảng cách hàng và đệm chữ ký để toàn bộ bảng sách rút gọn nằm trọn vẹn 100% trong 1 tờ A4, giúp khi in ra (hoặc lưu PDF) chỉ có **đúng 1 tờ giấy duy nhất**.

### 11. ⚡ Nút Tự Động Điền 1 Vào Ô Trống (Đặt Ngay Thanh Thu Phóng) & Tối Giản Nút Thừa
- **Nút bấm `⚡ Điền 1 ô trống` ngay trên thanh thu phóng**: Được bố trí nổi bật ngay cạnh cụm nút Thu Phóng và Ghép Xen Kẽ Lớp. Bạn chỉ cần bấm nút này 1 lần, hệ thống sẽ **tự động xác định tất cả các dòng sách đang để trống và điền số lượng 1 vào**, đồng thời **giữ nguyên tuyệt đối các ô bạn đã nhập số khác** (ví dụ: dòng *Đạo đức 1* đã nhập số 2 sẽ giữ nguyên là 2). *(Bạn cũng có thể nhấp đúp chuột vào tiêu đề cột `SỐ LƯỢNG` trên bảng để thực hiện nhanh).*
- **Đã xóa hoàn toàn nút dư dưới bảng**: Đã loại bỏ triệt để nút bấm `+ Thêm dòng sách mới` và `+ Thêm nhóm...` bên dưới bảng sách để bảng hiển thị liền mạch với phần chữ ký, không gây rối mắt và giải phóng tối đa diện tích in ấn. Mọi thao tác thêm/xóa dòng sách đều được thực hiện tiện lợi qua thanh điều khiển nổi khi rê chuột vào từng dòng.
- **Nút bấm bổ trợ trên thanh cài đặt**: Thanh bên phải bổ sung thêm 2 nút thao tác nhanh: **`⚡ Điền 1 vào ô trống`** và **`🧹 Xóa trắng`**.

### 12. ✍️ Signature Góc Phải, Đổi "Chủ Cửa Hàng" & Tải Ảnh Con Dấu / Chữ Ký
- **Thương hiệu / Signature góc phải tờ giấy**: Ở góc trên bên phải mỗi phiếu xuất hiện dòng thông tin thương hiệu thanh lịch (mặc định theo từng lớp: `VPP Thanh Tâm - Lớp 1`, `VPP Thanh Tâm - Lớp 2`...). Đối với khổ A5 đôi, dòng chữ này xuất hiện **độc lập ở góc phải của cả 2 nửa phiếu**. Bạn có thể nhấp chuột trực tiếp vào dòng này để chỉnh sửa tên cửa hàng/thương hiệu tùy ý.
- **Ký tên Chủ Cửa Hàng**: Ô ký tên hành chính được đổi mặc định thành **CHỦ CỬA HÀNG** (có thể bấm vào để chỉnh sửa nếu muốn).
- **Tải ảnh chữ ký / con dấu**: Thanh cài đặt bên phải có tính năng **"📷 Tải ảnh chữ ký / con dấu"** (hoặc bạn có thể nhấp trực tiếp vào ô ký tên trên phiếu để chọn ảnh). Ảnh tải lên sẽ hiển thị sắc nét, vừa vặn ngay trong ô ký tên khi in ấn hoặc lưu PDF.
- **Hoàn thiện tính năng Ghép Đôi A5**: Đã loại bỏ chữ "cắt đôi A5" ở giữa để lại đường phân cách đứt nét tinh tế. Sửa dứt điểm lỗi chỉnh giá ở nửa bên trái làm nhân đôi sang nửa bên phải, và lỗi chỉnh giá bên phải không cập nhật. Giờ đây cả 2 nửa phiếu hoạt động và tính tổng tiền hoàn toàn độc lập!

### 13. 🎯 Tối Ưu Mới Nhất: Đồng Bộ Bản In, Bảng In Chuẩn & Chuyển Định Dạng Lên Header
- **Đồng bộ bật/tắt chữ ký & tùy chọn trên cả 2 nửa phiếu A5**: Khi bỏ chọn "Hiển thị phần chữ ký", cả 2 nửa trang (kể cả khi ghép xen kẽ 2 khối lớp khác nhau) đều đồng loạt ẩn chữ ký, không còn tình trạng chỉ mất chữ ký ở một bên.
- **Tối giản nhãn checkbox**: Đã đổi nhãn tùy chọn thành **`Hiển thị phần chữ ký`** (loại bỏ chữ "phụ huynh").
- **Chuẩn hóa cột Thành tiền & sửa dứt điểm lỗi bảng khi in**:
  - Tùy chọn hiển thị cột Thành tiền được đồng bộ tuyệt đối giữa 2 nửa trang A5.
  - Khi chưa nhập số lượng (hoặc số lượng bằng 0), ô Thành tiền hiển thị để trống thay vì hiển thị một hàng số `0` gây rối mắt.
  - Bảng in A5 được định nghĩa kích thước cột tối ưu (`col-stt`, `col-price`, `col-qty`, `col-subtotal`), đảm bảo 100% không bị tràn viền, không bị cắt chữ header hay đè dòng tổng cộng khi in.
- **Signature góc phải chỉ hiển thị khi in (ẩn trên màn hình sửa)**: Dòng thương hiệu `VPP Thanh Tâm - Lớp ...` được ẩn trên giao diện soạn thảo trên màn hình và tự động xuất hiện chuẩn mực ở góc trên bên phải của mỗi phiếu khi bấm In / Lưu PDF. Người dùng có thể tùy chỉnh tên signature ngay trong bảng Tùy chọn in bên phải.
- **Đưa nút chọn Định dạng lên thanh Header trên cùng**: Hộp chọn định dạng in (**Khổ A4 đơn** vs **Khổ A5 tiết kiệm - 2 phiếu / trang A4**) được bố trí ngay trên thanh tiêu đề ứng dụng (Header) cạnh logo, đồng bộ 2 chiều với thanh cài đặt bên phải để thao tác tức thì.

### 14. 🛠️ Tinh Chỉnh In Ấn: Tiêu Đề Đơn Giản, Đổi "SL" & Bảng In Chuẩn Khổ
- **Không còn dòng tiêu đề trùng lặp trên đầu trang in**: Khi bấm in (khổ A5 đôi hoặc A4 đơn), hệ thống tự động để trống tiêu đề trang của trình duyệt để không in dòng chữ dư thừa ở mép trên cùng. Chỉ có thông tin thương hiệu góc phải trên từng phiếu được in ấn rõ nét.
- **Tối giản cài đặt**: Đã loại bỏ ô nhập Signature trong thanh bên phải để giữ giao diện gọn gàng, hệ thống tự động gán mặc định thương hiệu chuẩn theo từng lớp (`VPP Thanh Tâm - Lớp 1` đến `12`).
- **Đổi tiêu đề cột thành "SL"**: Tiêu đề cột `SỐ LƯỢNG` được đổi thành `SL` ngắn gọn, không bao giờ bị ngắt dòng hay tràn ô.
- **Sửa dứt điểm lỗi mất bảng / cắt chữ khi in 1 trang**: Tối ưu độ rộng cột (`col-stt`, `col-name`, `col-price`, `col-qty`, `col-subtotal`), bật `white-space: nowrap` cho tiêu đề và loại bỏ `overflow: hidden` trên khung bảng in, giúp bảng in A4 và A5 luôn hiển thị đầy đủ 100% các cột, viền bảng và số tiền tổng cộng mà không bị cắt xén.

### 15. 🖨️ Chuẩn Hóa Bản In Tuyệt Đối: Triệt Tiêu URL/Date & Chống Mất Nội Dung
- **Triệt tiêu hoàn toàn đường dẫn URL và ngày giờ trên đầu trang (`margin: 0 !important`)**: Thiết lập chuẩn `@page { margin: 0 !important; }` để trình duyệt Chrome/Edge không có khoảng trống lề để chèn ngày giờ và đường dẫn URL `127.0.0.1...` ở mép trên cùng của bản in.
- **Sửa dứt điểm hiện tượng mất dòng sách khi in A5 đôi (`table/table-cell print layout`)**:
  - Chuyển đổi kiến trúc in ấn từ CSS Grid/Flexbox sang Table/Table-cell layout chuẩn máy in. Khắc phục hoàn toàn lỗi cố hữu của Chrome khi in CSS Grid làm rơi rụng hoặc cắt xén các dòng sách từ dòng 4 trở đi.
  - Tối ưu mật độ in ấn khổ A5 (giảm đệm dòng, co nhỏ tiêu đề vừa vặn) đảm bảo cả 2 nửa phiếu (kể cả những khối lớp dài 18 sách như Lớp 9) đều nằm trọn vẹn 100% trong đúng 1 trang giấy duy nhất.
- **Tự động gắn đúng tên lớp cho Signature góc phải**: Hệ thống kiểm tra và tự động sửa các lỗi gán nhầm tên lớp (ví dụ: mở Lớp 8 thì luôn hiển thị chính xác `VPP Thanh Tâm - Lớp 8`, không bị vướng nhầm `Lớp 9`).

---

## 🚀 Hướng Dẫn Deploy Lên GitHub Pages (30 Giây)

1. Đẩy mã nguồn lên GitHub:
   ```bash
   git add index.html README.md
   git commit -m "feat: 12 classes pre-populated, per-class standard templates, 2xA5 on A4 print mode, right settings panel"
   git push origin main
   ```
2. Trên GitHub, vào **Settings** -> **Pages**.
3. Tại **Build and deployment** -> **Source**: Chọn `Deploy from a branch` -> Nhánh `main` -> thư mục `/(root)` -> Nhấn **Save**.
4. Truy cập website tại: `https://<username>.github.io/<tên-repo>/`
