# HyDict Desktop Releases 🚀

> **HyDict Desktop** — Ứng dụng từ điển thông minh đa ngôn ngữ (Tiếng Trung 🇨🇳, Tiếng Anh 🇬🇧, Tiếng Nhật 🇯🇵) chuyên sâu cho việc tra cứu tức thì, học tập thẻ ghi nhớ Anki, chụp OCR màn hình, lồng tiếng phụ đề video bằng AI và quản lý tài liệu học tập toàn diện trên hệ điều hành Windows.

---

## 📥 Tải Về Phiên Bản Mới Nhất: v2.7.0

| Gói Tải Về | Tệp Tin | Kích Thước | Mô Tả & Tính Năng |
| :--- | :--- | :--- | :--- |
| **Bản Cài Đặt ZIP (Khuyên Dùng)** | [**HyDict-v2.7.0-Setup.zip**](https://github.com/tahiep2012/HyDict-Releases/releases/download/v2.7.0/HyDict-v2.7.0-Setup.zip)<br>*(hoặc [HyDict-v2.7.0-Setup.exe](https://github.com/tahiep2012/HyDict-Releases/releases/download/v2.7.0/HyDict-v2.7.0-Setup.exe))* | `~53.5 MB` | • Trình cài đặt tự động đầy đủ tính năng đóng gói trong file nén .zip an toàn.<br>• **Có nút check tạo Shortcut ra màn hình Desktop (bật sẵn)**.<br>• Tự động kích hoạt gói OCR Tiếng Nhật Windows.<br>• Tự động tạo lối tắt trong Start Menu & tích hợp uninstaller.<br>• Đóng gói sẵn toàn bộ cơ sở dữ liệu từ điển offline. |
| **Bản Portable (Chạy Ngay)** | [**HyDict-v2.7.0-windows-x64.zip**](https://github.com/tahiep2012/HyDict-Releases/releases/download/v2.7.0/HyDict-v2.7.0-windows-x64.zip) | `~53.6 MB` | • Dành cho người dùng muốn giải nén là chạy ngay không cần cài đặt.<br>• Phù hợp lưu trữ trong USB hoặc môi trường di động. |

---

## ✨ Điểm Mới Nổi Bật Trong Phiên Bản v2.7.0

1. **Trung Tâm Tài Liệu Học Tập Toàn Diện (Learning Materials Hub)**:
   - Thêm tab điều hướng mới **Tài Liệu** trên thanh bên chính của ứng dụng.
   - Quản trị toàn bộ kho học liệu bài giảng theo cấu trúc cây thư mục và khóa học phân cấp đa tầng (Hierarchical Folder Tree).
   - Hỗ trợ lưu trữ, tải lên và xem trước tất cả các định dạng học tập: Video bài giảng, tài liệu PDF, tệp âm thanh nghe hiểu MP3, hình ảnh và ghi chú văn bản.
   - Tích hợp trình phát media chuyên dụng (Study Video Player) hỗ trợ phát video mượt mà kèm phụ đề song ngữ.

2. **Hệ Thống Chế Độ Xem Chuẩn Phong Cách Windows Explorer (Windows View Modes)**:
   - Bổ sung menu lựa chọn phong cách hiển thị trực quan: **Biểu tượng lớn (Large Icons)**, **Chi tiết (Details)** kèm bảng kích thước/ngày sửa đổi, **Danh sách (List)**, và **Dạng ô (Tiles)**.
   - **Ghi nhớ cấu hình vĩnh viễn (UI Persistence)**: Toàn bộ tùy chọn của người dùng (`viewMode`, thứ tự sắp xếp `sortKey`, trạng thái đóng/mở thanh thông tin `isInspectorOpen`, thư mục đang chọn) được lưu tự động vào `localStorage`, đảm bảo không bao giờ bị reset về mặc định khi khởi động lại máy hoặc mở lại phần mềm.

3. **Menu Thao Tác Chuột Phải Thư Mục (Context Menu)**:
   - Hỗ trợ nhấp chuột phải trực tiếp vào các mục trong danh sách khóa học / thư mục để:
     - `+ Tạo thư mục con`: Nhanh chóng thêm phân nhánh mới.
     - `✏️ Đổi tên thư mục`: Hộp thoại chỉnh sửa tên trực quan.
     - `🗑️ Xóa thư mục`: Hiển thị hộp thoại cảnh báo xác nhận an toàn trước khi xóa nhằm bảo vệ dữ liệu học tập.

4. **Tích Hợp Sâu Hệ Thống Tệp Windows Native**:
   - Nút **"Thay đổi"** nơi lưu trữ kích hoạt trực tiếp hộp thoại chọn thư mục gốc Windows Explorer native (`select_storage_folder`).
   - Nút mở nhanh thư mục lưu trữ trực tiếp trong ứng dụng Windows Explorer (`open_in_explorer`).
   - Tinh gọn thanh điều hướng bên trái: Loại bỏ khu vực thẻ phân loại rườm rà, tập trung hiển thị tag trong bảng chi tiết và xem trước bài giảng.

5. **Menu Điều Hướng Tương Thích Phong Cách Google Chrome (Chrome Responsive Drawer Menu)**:
   - Khi thu nhỏ cửa sổ ứng dụng (Restore Down / thu hẹp chiều rộng), thanh menu dọc cố định tự động thu gọn tinh tế, chuyển sang thanh tiêu đề nhỏ gọn kèm nút Hamburger (`☰`).
   - Nhấp vào nút Hamburger mở thanh Drawer trượt mượt mà kèm lớp phủ mờ tối (darkened backdrop), tự động đóng lại khi chọn tab, bấm ra ngoài hoặc nhấn phím `Escape`.
   - Trả lại toàn bộ không gian ngang cho giao diện học liệu khi ở màn hình nhỏ.

6. **Bố Cục Cột Lưới Bất Biến (Invariant CSS Grid Layout)**:
   - Tái thiết kế bảng danh sách tài liệu (`MaterialDetailsTable`) theo cấu trúc CSS Grid chia cột cố định chuẩn xác (`minmax(220px, 1fr) 120px 115px 105px 110px`).
   - Đảm bảo 100% không bao giờ bị gãy thành 2 dòng ở các cột `NGÀY THÊM`, `LOẠI TỆP`, `KÍCH THƯỚC`, `THAO TÁC`, các huy hiệu định dạng (`Video MP4`, `Sách PDF`, `Âm thanh`, `Excel / Word`) và nút hành động khi co giãn kích thước cửa sổ.

---

## 🌟 Nhật Ký Các Phiên Bản Trước

### Phiên Bản v2.6.10:
1. **Tự Động Lồng Tiếng Phụ Đề Video Ngầm (Auto-Dubbing Watchdog)**: Tự động tổng hợp âm thanh ngay khi câu phụ đề được dịch.
2. **Nâng Cấp Bể Xử Lý 8 Luồng Song Song Siêu Tốc (8-Worker Pool)**: Tăng tốc tạo giọng đọc Edge Neural AI lên gấp đôi (~7-9 giây hoàn tất video).
3. **Huy Hiệu Trạng Thái Lồng Tiếng Thời Gian Thực**: Nhãn xanh `✓ Đã lồng tiếng` và nhãn cam `⏳ Đang lồng tiếng`.
4. **Trình Tải Phụ Đề .SRT Đa Định Dạng**: Tùy chọn tải phụ đề gốc hoặc phụ đề tiếng Việt qua Windows Explorer dialog.

### Phiên Bản v2.6.9:
1. **Lọc Câu Ví Dụ Tự Động Theo Chữ Giản Thể & Phồn Thể**: Ẩn câu có chữ đối lập, chỉ hiển thị câu thuần thể chữ người dùng chọn.
2. **Empty State Thông Minh Cho Câu Ví Dụ**: Gợi ý tạo câu ví dụ AI đúng chuẩn thể chữ.

### Phiên Bản v2.6.8:
1. **Tùy Chọn Chữ Giản / Phồn Thể Trong Cài Đặt**: Chuyển đổi hiển thị linh hoạt.
2. **Sửa Lỗi Nhận Diện Trùng Lặp Thẻ Anki**: Tiết kiệm token AI.

### Phiên Bản v2.6.7:
1. **Tự Động Cài Đặt AnkiConnect 100% Offline (Zero-Configuration)**.
2. **Tự Động Khởi Chạy Anki Desktop Khi Thêm Thẻ**.
3. **Kiểm Tra Trùng Lặp Thẻ Trước Khi Gọi AI / Sinh Âm Thanh**.
4. **Tự Động Sinh Ảnh Minh Họa AI Đa Ngôn Ngữ**.
5. **Khóa Chết Cơ Chế Bảo Vệ Bản Quyền Phần Mềm (Hardware Machine ID)**.

### Phiên Bản v2.6.0:
1. **Hệ Sinh Thái Từ Điển Tam Ngữ Hoàn Chỉnh (Tri-Lingual Engine)**: Tiếng Trung 🇨🇳, Tiếng Anh 🇬🇧, Tiếng Nhật 🇯🇵.
2. **Gợi Ý Từ Khóa Đa Ngữ Thông Minh (Auto-Suggestions)**.
3. **Đồng Bộ Anki Card Tự Động Theo Từng Ngôn Ngữ**.
4. **Studio Lồng Tiếng Video AI & Gemini 1-Click BYOK**.
5. **Công Nghệ Chụp OCR Màn Hình Tam Ngữ Tối Ưu**.

---

## 💻 Yêu Cầu Hệ Thống

- **Hệ điều hành**: Windows 10 (64-bit) hoặc Windows 11 (64-bit).
- **Runtime**: Microsoft Edge WebView2 Evergreen Runtime (đã tích hợp sẵn trên Windows 10/11).
- **RAM**: Tối thiểu 2 GB (khuyến nghị 4 GB trở lên).
- **Dung lượng trống**: 300 MB.

---

## 📖 Hướng Dẫn Cài Đặt

1. Tải về tệp tin [**HyDict-v2.7.0-Setup.zip**](https://github.com/tahiep2012/HyDict-Releases/releases/download/v2.7.0/HyDict-v2.7.0-Setup.zip) hoặc [**HyDict-v2.7.0-Setup.exe**](https://github.com/tahiep2012/HyDict-Releases/releases/download/v2.7.0/HyDict-v2.7.0-Setup.exe).
2. Nhấp đúp vào tệp tin để mở trình cài đặt.
3. Giữ nguyên dấu tích chọn **`☑ Tạo shortcut ra màn hình desktop`** nếu bạn muốn có biểu tượng HyDict trên màn hình Desktop.
4. Nhấn **Cài đặt**. Quá trình cài đặt hoàn tất trong vài giây và ứng dụng sẽ tự động khởi động.

---

## 📞 Hỗ Trợ & Bản Quyền

- Tác giả: **Võ Tá Hiệp** ([@tahiep2012](https://github.com/tahiep2012))
- Dự án chính: [https://github.com/tahiep2012/HyDict](https://github.com/tahiep2012/HyDict)
