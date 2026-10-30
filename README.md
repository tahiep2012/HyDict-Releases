# HyDict Desktop Releases 🚀

> **HyDict Desktop** — Ứng dụng từ điển thông minh đa ngôn ngữ (Tiếng Trung 🇨🇳, Tiếng Anh 🇬🇧, Tiếng Nhật 🇯🇵) chuyên sâu cho việc tra cứu tức thì, học tập thẻ ghi nhớ Anki, chụp OCR màn hình, lồng tiếng phụ đề video bằng AI và quản lý tài liệu học tập toàn diện trên hệ điều hành Windows.

---

## 📥 Tải Về Phiên Bản Mới Nhất: v2.7.0

| Gói Tải Về | Tệp Tin | Kích Thước | Mô Tả & Tính Năng |
| :--- | :--- | :--- | :--- |
| **Bản Cài Đặt ZIP (Khuyên Dùng)** | [**HyDict-v2.7.0-Setup.zip**](https://github.com/tahiep2012/HyDict-Releases/releases/download/v2.7.0/HyDict-v2.7.0-Setup.zip)<br>*(hoặc [HyDict-v2.7.0-Setup.exe](https://github.com/tahiep2012/HyDict-Releases/releases/download/v2.7.0/HyDict-v2.7.0-Setup.exe))* | `~75.8 MB` | • Trình cài đặt tự động đầy đủ tính năng đóng gói trong file nén .zip an toàn.<br>• **Có nút check tạo Shortcut ra màn hình Desktop (bật sẵn)**.<br>• Tích hợp sẵn engine `yt-dlp.exe` di động trong thư mục `bin\`.<br>• Tự động kích hoạt gói OCR Tiếng Nhật Windows.<br>• Tự động tạo lối tắt trong Start Menu & tích hợp uninstaller.<br>• Đóng gói sẵn toàn bộ cơ sở dữ liệu từ điển offline. |
| **Bản Portable (Chạy Ngay)** | [**HyDict-v2.7.0-windows-x64.zip**](https://github.com/tahiep2012/HyDict-Releases/releases/download/v2.7.0/HyDict-v2.7.0-windows-x64.zip) | `~76.0 MB` | • Dành cho người dùng muốn giải nén là chạy ngay không cần cài đặt.<br>• Tích hợp sẵn `bin\yt-dlp.exe` di động tự động nhận diện theo đường dẫn tương đối.<br>• Phù hợp lưu trữ trong USB hoặc môi trường di động. |

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

7. **Tích Hợp Hệ Thống Tệp Windows Native Thực Tế (100% Real Native Filesystem)**:
   - Tích hợp hộp thoại chọn tệp native Windows (`rfd::FileDialog`) cho phép chọn trực tiếp các tệp từ máy tính (`.mp4`, `.pdf`, `.docx`, `.xlsx`, `.mp3`...).
   - Tự động sao chép an toàn và đồng bộ tệp vật lý vào thư mục tài liệu lưu trữ (`storagePath/[Thư mục con]`) kèm cơ chế chống trùng lặp tên tệp (`filename (1).ext`).

8. **Đồng Bộ Hóa Thao Tác Thư Mục Thật Trên Ổ Cứng (Physical Folder Sync)**:
   - Tính năng **Đổi tên thư mục** (`rename_physical_folder`) và **Xóa thư mục** (`delete_physical_folder`) đồng bộ trực tiếp với thư mục vật lý thật trên ổ đĩa Windows bằng Rust native (`std::fs::rename` và `std::fs::remove_dir_all`).
   - Tự động cập nhật đường dẫn tài liệu con và cơ chế bảo vệ chống xóa nhầm thư mục gốc.

9. **Tích Hợp Sẵn Engine yt-dlp Di Động Đa Nền Tảng (Portable yt-dlp Engine)**:
   - Tích hợp sẵn binary chính thức `yt-dlp.exe` v2026.10.26 trong thư mục `bin\` ngang hàng với file `HyDict.exe`. Tự động nhận diện đường dẫn di động tương đối, copy sang bất kỳ máy tính hoặc ổ đĩa nào đều chạy ngay lập tức mà không cần cài đặt thêm Python hay cấu hình môi trường.
   - Hỗ trợ tải trực tiếp video bài giảng từ đa nền tảng (YouTube, Facebook,...) về ổ cứng với độ phân giải cao 1080p Full HD hoặc bóc tách riêng file âm thanh MP3.
   - Tự động tải kèm phụ đề song ngữ `.srt` / `.vtt`, ảnh bìa thumbnail chất lượng cao và thanh tiến trình thời gian thực (`percent`, `speed`, `ETA`).

10. **Bảng Cài Đặt Dữ Liệu Chuyên Sâu & Rào Chắn Bản Quyền Gói Vĩnh Viễn (Data Settings & Lifetime License Gate)**:
    - Bổ sung bảng cài đặt mới **Dữ Liệu** nằm ngay phía trên bảng "Hệ thống" trong tab Cài Đặt, tuân thủ nguyên tắc thiết kế tinh gọn (Progressive Disclosure) và Zero-Raw-HTML của Design System.
    - Quản lý toàn diện các thông số của kho học liệu: Nơi lưu trữ, tự động phân nhóm thư mục con, cơ chế chống trùng lặp, đồng bộ xóa tệp thật, chế độ xem mặc định, và cấu hình nâng cao cho engine tải video `yt-dlp` (chất lượng ưu tiên, định dạng tệp, số luồng tải tăng tốc đa luồng 4/8/1, ngôn ngữ phụ đề).
    - **Rào chắn bản quyền Gói Vĩnh Viễn (Lifetime Gate)**: Tab **"Tài Liệu"** trên thanh bên chính và bảng **"Dữ Liệu"** trong Cài Đặt chỉ hiển thị dành riêng cho tài khoản sở hữu gói bản quyền Vĩnh Viễn (`LIFETIME`). Mọi gói bản quyền khác (Free, Dùng thử, Gói theo tháng/năm) đều tự động ẩn hoàn toàn để bảo vệ tính độc quyền của tính năng cao cấp.

---

## 🛠️ Hướng Dẫn Nâng Cấp & Cài Đặt

1. **Người dùng mới**:
   - Tải tệp `HyDict-v2.7.0-Setup.zip`, giải nén và chạy file `HyDict-v2.7.0-Setup.exe`.
   - Trình cài đặt sẽ tự động kích hoạt tính năng tạo Shortcut ngoài màn hình Desktop và thiết lập môi trường hoàn tất.
2. **Người dùng đang sử dụng phiên bản cũ**:
   - Thoát hoàn toàn ứng dụng HyDict (chuột phải biểu tượng ở khay hệ thống Tray icon -> Thoát ứng dụng).
   - Chạy bộ cài mới để tự động cập nhật đè mà không làm mất dữ liệu từ vựng, sổ từ hay tài liệu học tập hiện có.

---

*HyDict Team — Tối ưu hóa trải nghiệm học ngoại ngữ toàn diện trên Windows.*
