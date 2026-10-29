# HyDict Desktop Releases 🚀

> **HyDict Desktop** — Ứng dụng từ điển thông minh đa ngôn ngữ (Tiếng Trung 🇨🇳, Tiếng Anh 🇬🇧, Tiếng Nhật 🇯🇵) chuyên sâu cho việc tra cứu tức thì, học tập thẻ ghi nhớ Anki, chụp OCR màn hình và lồng tiếng phụ đề video bằng AI trên hệ điều hành Windows.

---

## 📥 Tải Về Phiên Bản Mới Nhất: v2.6.10

| Gói Tải Về | Tệp Tin | Kích Thước | Mô Tả & Tính Năng |
| :--- | :--- | :--- | :--- |
| **Bản Cài Đặt ZIP (Khuyên Dùng)** | [**HyDict-v2.6.10-Setup.zip**](https://github.com/tahiep2012/HyDict-Releases/releases/download/v2.6.10/HyDict-v2.6.10-Setup.zip)<br>*(hoặc [HyDict-v2.6.10-Setup.exe](https://github.com/tahiep2012/HyDict-Releases/releases/download/v2.6.10/HyDict-v2.6.10-Setup.exe))* | `~53.5 MB` | • Trình cài đặt tự động đầy đủ tính năng đóng gói trong file nén .zip an toàn.<br>• **Có nút check tạo Shortcut ra màn hình Desktop (bật sẵn)**.<br>• Tự động kích hoạt gói OCR Tiếng Nhật Windows.<br>• Tự động tạo lối tắt trong Start Menu & tích hợp uninstaller.<br>• Đóng gói sẵn toàn bộ cơ sở dữ liệu từ điển offline. |
| **Bản Portable (Chạy Ngay)** | [**HyDict-v2.6.10-windows-x64.zip**](https://github.com/tahiep2012/HyDict-Releases/releases/download/v2.6.10/HyDict-v2.6.10-windows-x64.zip) | `~53.6 MB` | • Dành cho người dùng muốn giải nén là chạy ngay không cần cài đặt.<br>• Phù hợp lưu trữ trong USB hoặc môi trường di động. |

---

## ✨ Điểm Mới Nổi Bật Trong Phiên Bản v2.6.10

1. **Tự Động Lồng Tiếng Phụ Đề Video Ngầm (Auto-Dubbing Watchdog)**:
   - Hệ thống tự động phát hiện các câu phụ đề đã được dịch sang tiếng Việt (`textDubbed`) để tự động bốc vào hàng đợi tổng hợp giọng đọc AI ngay lập tức mà người dùng không cần phải bấm Play trước.
2. **Nâng Cấp Bể Xử Lý 8 Luồng Song Song Siêu Tốc (8-Worker Pool)**:
   - Tăng gấp đôi tốc độ tạo giọng đọc Microsoft Edge Neural AI lên 8 luồng đồng thời (`Promise.all` 8 câu một lúc).
   - Rút ngắn khoảng nghỉ giữa các lô xuống 10ms, cho phép hoàn tất lồng tiếng video ~300 câu chỉ trong 7–9 giây.
3. **Huy Hiệu Trạng Thái Lồng Tiếng Thời Gian Thực**:
   - Hiển thị nhãn xanh lá `✓ Đã lồng tiếng` khi file âm thanh đã sẵn sàng trong bộ nhớ RAM; hiển thị nhãn cam xoay `⏳ Đang lồng tiếng` khi câu thoại đang trong hàng đợi tạo âm thanh.
4. **Trình Tải Phụ Đề .SRT Đa Định Dạng (Native Save Dialog)**:
   - Bổ sung menu thả xuống tải phụ đề 2 tùy chọn: **Phụ đề gốc** (nguyên bản ngôn ngữ video) và **Phụ đề Tiếng Việt** (đã đồng bộ dịch thuật), hỗ trợ lưu tệp trực tiếp qua hộp thoại Windows Explorer native.

---

## 🌟 Nhật Ký Các Phiên Bản Trước

### Phiên Bản v2.6.9:
1. **Lọc Câu Ví Dụ Tự Động Theo Chữ Giản Thể & Phồn Thể**: Toàn bộ câu ví dụ có sẵn trong từ điển nếu có chứa ký tự chữ Hán đối lập sẽ tự động bị ẩn đi 100%, chỉ hiển thị câu thuần thể chữ người dùng đang chọn.
2. **Empty State Thông Minh Cho Câu Ví Dụ**: Hướng dẫn bấm nút tạo câu ví dụ AI đúng chuẩn thể chữ đang chọn.

### Phiên Bản v2.6.8:
1. **Tùy Chọn Chữ Giản / Phồn Thể Trong Cài Đặt**: Hỗ trợ chuyển đổi hiển thị chữ Hán linh hoạt.
2. **Sửa Lỗi Nhận Diện Trùng Lặp Thẻ Anki**: Kiểm tra trùng thẻ chính xác và tiết kiệm token AI.

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

1. Tải về tệp tin [**HyDict-v2.6.10-Setup.zip**](https://github.com/tahiep2012/HyDict-Releases/releases/download/v2.6.10/HyDict-v2.6.10-Setup.zip) hoặc [**HyDict-v2.6.10-Setup.exe**](https://github.com/tahiep2012/HyDict-Releases/releases/download/v2.6.10/HyDict-v2.6.10-Setup.exe).
2. Nhấp đúp vào tệp tin để mở trình cài đặt.
3. Giữ nguyên dấu tích chọn **`☑ Tạo shortcut ra màn hình desktop`** nếu bạn muốn có biểu tượng HyDict trên màn hình Desktop.
4. Nhấn **Cài đặt**. Quá trình cài đặt hoàn tất trong vài giây và ứng dụng sẽ tự động khởi động.

---

## 📞 Hỗ Trợ & Bản Quyền

- Tác giả: **Võ Tá Hiệp** ([@tahiep2012](https://github.com/tahiep2012))
- Dự án chính: [https://github.com/tahiep2012/HyDict](https://github.com/tahiep2012/HyDict)
