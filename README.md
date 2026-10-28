# HyDict Desktop Releases 🚀

> **HyDict Desktop** — Ứng dụng từ điển thông minh đa ngôn ngữ (Tiếng Trung 🇨🇳, Tiếng Anh 🇬🇧, Tiếng Nhật 🇯🇵) chuyên sâu cho việc tra cứu tức thì, học tập thẻ ghi nhớ Anki, chụp OCR màn hình và lồng tiếng phụ đề video bằng AI trên hệ điều hành Windows.

---

## 📥 Tải Về Phiên Bản Mới Nhất: v2.6.7

| Gói Tải Về | Tệp Tin | Kích Thước | Mô Tả & Tính Năng |
| :--- | :--- | :--- | :--- |
| **Bản Cài Đặt ZIP (Khuyên Dùng)** | [**HyDict-v2.6.7-Setup.zip**](https://github.com/tahiep2012/HyDict-Releases/releases/download/v2.6.7/HyDict-v2.6.7-Setup.zip)<br>*(hoặc [HyDict-v2.6.7-Setup.exe](https://github.com/tahiep2012/HyDict-Releases/releases/download/v2.6.7/HyDict-v2.6.7-Setup.exe))* | `~53.5 MB` | • Trình cài đặt tự động đầy đủ tính năng đóng gói trong file nén .zip an toàn.<br>• **Có nút check tạo Shortcut ra màn hình Desktop (bật sẵn)**.<br>• Tự động kích hoạt gói OCR Tiếng Nhật Windows.<br>• Tự động tạo lối tắt trong Start Menu & tích hợp uninstaller.<br>• Đóng gói sẵn toàn bộ cơ sở dữ liệu từ điển offline. |
| **Bản Portable (Chạy Ngay)** | [**HyDict-v2.6.7-windows-x64.zip**](https://github.com/tahiep2012/HyDict-Releases/releases/download/v2.6.7/HyDict-v2.6.7-windows-x64.zip) | `~56.2 MB` | • Dành cho người dùng muốn giải nén là chạy ngay không cần cài đặt.<br>• Phù hợp lưu trữ trong USB hoặc môi trường di động. |

---

## ✨ Điểm Mới Nổi Bật Trong Phiên Bản v2.6.7

1. **Tự Động Cài Đặt AnkiConnect 100% Offline (Zero-Configuration)**:
   - Gói add-on AnkiConnect (`2055492159`) dung lượng ~91 KB được nhúng trực tiếp vào file thực thi của HyDict.
   - Khi bấm **"Thêm vào Anki"**, nếu phát hiện máy tính chưa có AnkiConnect, HyDict tự động giải nén và nạp toàn bộ mã nguồn add-on vào thư mục Anki của máy chỉ trong 10ms mà **không cần kết nối Internet**.
   - Cấu hình sẵn CORS (`http://localhost`, `http://tauri.localhost`, `*`) ngăn chặn triệt để mọi lỗi chặn kết nối giữa Webview và Anki.
   - Bổ sung nút bấm **`[Tự động cài AnkiConnect (1-Click)]`** nổi bật trong phần Cài đặt Hệ thống để người dùng có thể kích hoạt chủ động bất kỳ lúc nào.

2. **Tự Động Khởi Chạy Anki Desktop Khi Thêm Thẻ**:
   - Khi bấm nút **"Thêm vào Anki"** mà phần mềm Anki Desktop đang đóng, HyDict tự động quét và kích hoạt `Anki.exe` chạy nền độc lập.
   - Hệ thống tự động chờ AnkiConnect sẵn sàng và tiếp tục đẩy thẻ mới vào Anki mượt mà, không gây ngắt quãng trải nghiệm người dùng.

3. **Kiểm Tra Trùng Lặp Thẻ Trước Khi Gọi AI / Sinh Âm Thanh (Pre-check Duplicates)**:
   - Cơ chế kiểm tra siêu tốc (~30ms) qua AnkiConnect được kích hoạt ngay bước đầu tiên để xác định từ vựng đã tồn tại trong bộ bài hay chưa.
   - Nếu từ đã có trong Anki: Lập tức dừng quy trình, **tiết kiệm 100% token AI (sinh câu/ảnh)** và **không tốn thời gian tạo audio TTS**, đồng thời chuyển nút sang trạng thái thân thiện: `✓ Đã có trong Anki`.

4. **Tự Động Sinh Ảnh Minh Họa AI Đa Ngôn Ngữ (Trung - Anh - Nhật)**:
   - Hỗ trợ tạo ảnh trực quan theo phong cách đã thiết lập (Anime, Realistic, Cyberpunk, 3D Render...) cho từ vựng của cả 3 ngôn ngữ khi thêm vào Anki.
   - Tự động nhận diện trạng thái API Key: Tự vô hiệu hóa tính năng tạo ảnh khi chưa nhập Agnes API Key và tự kích hoạt lại ngay khi người dùng nạp Key.

5. **Khóa Chết Cơ Chế Bảo Vệ Bản Quyền Phần Mềm (Hardware Machine ID)**:
   - Token bản quyền được mã hóa và khóa cứng theo Hardware ID vật lý của bo mạch chủ / CPU thiết bị.
   - Tuyệt đối ngăn chặn sao chép phần mềm sang máy khác để sử dụng trái phép; tự động gửi tín hiệu hủy kích hoạt lên máy chủ API khi người dùng nhấn Hủy bản quyền.

6. **Tối Ưu Bố Cục Tab Đồng Bộ Anki & Tự Động Nén Setup.zip**:
   - Tái cấu trúc khu vực chọn **Bộ Deck** và **Loại thẻ** thành 2 hàng ngang độc lập, rộng rãi, chống tràn vỡ giao diện trên mọi kích thước màn hình.
   - Hiển thị đầy đủ nhãn nguồn ánh xạ trường mà không bị cắt cụt ba chấm.
   - Bộ cài đặt được tự động đóng gói thêm bản `.zip` giúp tải về nhanh chóng và không bị trình duyệt cảnh báo.

---

## 🌟 Nhật Ký Các Phiên Bản Trước

### Phiên Bản v2.6.0:
1. **Hệ Sinh Thái Từ Điển Tam Ngữ Hoàn Chỉnh (Tri-Lingual Engine)**: Tiếng Trung 🇨🇳, Tiếng Anh 🇬🇧, Tiếng Nhật 🇯🇵.
2. **Gợi Ý Từ Khóa Đa Ngữ Thông Minh (Auto-Suggestions)**: Tra xuôi và tra ngược tiếng Việt đa chiều.
3. **Đồng Bộ Anki Card Tự Động Theo Ngôn Ngữ**: Tự động nhận diện ngôn ngữ và giọng đọc Neural TTS tương ứng.
4. **Studio Lồng Tiếng Video AI & Gemini 1-Click BYOK**.
5. **Bộ Cài Đặt Windows Setup Hiện Đại**.
6. **Bảng Cài Đặt AI API Tinh Gọn & Tự Động Lưu Tức Thì (Instant Auto-Save)**.
7. **Trình Tạo Câu Ví Dụ AI Đa Ngữ & Khóa Kích Thước Cửa Sổ Chuẩn**.
8. **Công Nghệ Chụp OCR Màn Hình Tam Ngữ Tối Ưu (Tri-Lingual Screen OCR)**.
9. **Thuật Toán Xếp Hạng Ưu Tiên & Hợp Nhất Nghĩa Từ Đa Nghĩa (Polysemous Word Ranking & Merging)**.
10. **Bộ Nhận Diện Từ Loại Thông Minh (Smart POS Detector)**.

---

## 💻 Yêu Cầu Hệ Thống

- **Hệ điều hành**: Windows 10 (64-bit) hoặc Windows 11 (64-bit).
- **Runtime**: Microsoft Edge WebView2 Evergreen Runtime (đã tích hợp sẵn trên Windows 10/11).
- **RAM**: Tối thiểu 2 GB (khuyến nghị 4 GB trở lên).
- **Dung lượng trống**: 300 MB.

---

## 📖 Hướng Dẫn Cài Đặt

1. Tải về tệp tin [**HyDict-v2.6.7-Setup.zip**](https://github.com/tahiep2012/HyDict-Releases/releases/download/v2.6.7/HyDict-v2.6.7-Setup.zip) hoặc [**HyDict-v2.6.7-Setup.exe**](https://github.com/tahiep2012/HyDict-Releases/releases/download/v2.6.7/HyDict-v2.6.7-Setup.exe).
2. Nhấp đúp vào tệp tin để mở trình cài đặt.
3. Giữ nguyên dấu tích chọn **`☑ Tạo shortcut ra màn hình desktop`** nếu bạn muốn có biểu tượng HyDict trên màn hình Desktop.
4. Nhấn **Cài đặt**. Quá trình cài đặt hoàn tất trong vài giây và ứng dụng sẽ tự động khởi động.

---

## 📞 Hỗ Trợ & Bản Quyền

- Tác giả: **Võ Tá Hiệp** ([@tahiep2012](https://github.com/tahiep2012))
- Dự án chính: [https://github.com/tahiep2012/HyDict](https://github.com/tahiep2012/HyDict)
