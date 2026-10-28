# HyDict Desktop Releases 🚀

> **HyDict Desktop** — Ứng dụng từ điển thông minh đa ngôn ngữ (Tiếng Trung 🇨🇳, Tiếng Anh 🇬🇧, Tiếng Nhật 🇯🇵) chuyên sâu cho việc tra cứu tức thì, học tập thẻ ghi nhớ Anki, chụp OCR màn hình và lồng tiếng phụ đề video bằng AI trên hệ điều hành Windows.

---

## 📥 Tải Về Phiên Bản Mới Nhất: v2.6.8

| Gói Tải Về | Tệp Tin | Kích Thước | Mô Tả & Tính Năng |
| :--- | :--- | :--- | :--- |
| **Bản Cài Đặt ZIP (Khuyên Dùng)** | [**HyDict-v2.6.8-Setup.zip**](https://github.com/tahiep2012/HyDict-Releases/releases/download/v2.6.8/HyDict-v2.6.8-Setup.zip)<br>*(hoặc [HyDict-v2.6.8-Setup.exe](https://github.com/tahiep2012/HyDict-Releases/releases/download/v2.6.8/HyDict-v2.6.8-Setup.exe))* | `~45.5 MB` | • Trình cài đặt tự động đầy đủ tính năng đóng gói trong file nén .zip an toàn.<br>• **Có nút check tạo Shortcut ra màn hình Desktop (bật sẵn)**.<br>• Tự động kích hoạt gói OCR Tiếng Nhật Windows.<br>• Tự động tạo lối tắt trong Start Menu & tích hợp uninstaller.<br>• Đóng gói sẵn toàn bộ cơ sở dữ liệu từ điển offline. |
| **Bản Portable (Chạy Ngay)** | [**HyDict-v2.6.8-windows-x64.zip**](https://github.com/tahiep2012/HyDict-Releases/releases/download/v2.6.8/HyDict-v2.6.8-windows-x64.zip) | `~45.5 MB` | • Dành cho người dùng muốn giải nén là chạy ngay không cần cài đặt.<br>• Phù hợp lưu trữ trong USB hoặc môi trường di động. |

---

## ✨ Điểm Mới Nổi Bật Trong Phiên Bản v2.6.8

1. **Tùy Chọn Tạo Câu Ví Dụ AI Giản Thể & Phồn Thể Chuyên Biệt Cho Tiếng Trung**:
   - Bổ sung nút chuyển đổi trực quan `[ Giản thể | Phồn thể ]` ngay trên thanh công cụ phần *Câu ví dụ thực tế & AI* (chỉ kích hoạt riêng khi tra cứu từ điển tiếng Trung `zh`).
   - Cả hai mô hình AI (Google Gemini AI & Agnes AI) tự động sinh câu chuẩn xác 100% theo đúng thể chữ đã chọn.
   - Tự động map chữ Hán Phồn thể sang thẻ Anki khi người dùng kích hoạt chế độ Phồn thể.
   - Cho phép thiết lập thể chữ mặc định thuận tiện trong Cài đặt Hệ thống.

2. **Sửa Triệt Để Lỗi Báo Trùng Thẻ Anki Sai Lệch (Exact Match Sort Field Gate)**:
   - Nâng cấp hàm kiểm tra trùng lặp: Ưu tiên tuyệt đối kết quả chuẩn xác từ AnkiConnect (`canAddNotes`). Khi Anki xác nhận từ chưa có ở trường Sort/Word Field, phần mềm sẽ cho phép thêm ngay lập tức.
   - Khóa chặt phạm vi truy vấn tìm kiếm dự phòng chỉ ở trường từ vựng đầu tiên, loại bỏ hoàn toàn việc quét nhầm vào câu ví dụ (*Example*) hay phần giải nghĩa của từ khác trong bộ bài.

3. **Kế Thừa Toàn Bộ Hệ Thống Tự Động Hóa Từ Bản v2.6.7**:
   - **Tự động cài đặt AnkiConnect offline 100% (Zero-Configuration)**: Nhúng trực tiếp add-on `2055492159`, tự động cài đặt trong 10ms nếu máy chưa có, cấu hình sẵn CORS ngăn chặn lỗi kết nối.
   - **Tự động khởi chạy Anki Desktop**: Tự quét và chạy ngầm `Anki.exe` khi nhấn "Thêm vào Anki" nếu Anki chưa được mở.
   - **Pre-check trùng lặp thẻ**: Kiểm tra siêu tốc (~30ms) trước khi gọi AI/TTS, tiết kiệm 100% token AI và thời gian tạo âm thanh.
   - **Tự động sinh ảnh minh họa AI đa ngôn ngữ**: Tạo ảnh trực quan theo phong cách đã chọn (Anime, Realistic, Cyberpunk, 3D...) cho cả 3 ngôn ngữ Trung - Anh - Nhật.
   - **Bảo vệ bản quyền theo phần cứng (Hardware Machine ID)**: Khóa bản quyền theo thiết bị bo mạch chủ/CPU, chống sao chép trái phép.

---

## 🌟 Nhật Ký Các Phiên Bản Trước

### Phiên Bản v2.6.7:
- Tự động cài đặt AnkiConnect offline 1-click.
- Tự động khởi chạy Anki Desktop khi thêm thẻ.
- Pre-check trùng lặp thẻ trước khi gọi AI/TTS.
- Tự động sinh ảnh minh họa AI đa ngôn ngữ.

### Phiên Bản v2.6.0:
- Hệ sinh thái từ điển tam ngữ hoàn chỉnh (Tiếng Trung 🇨🇳, Tiếng Anh 🇬🇧, Tiếng Nhật 🇯🇵).
- Gợi ý từ khóa đa ngữ thông minh (Auto-Suggestions) đa chiều.
- Đồng bộ Anki Card tự động theo từng ngôn ngữ và giọng đọc Neural TTS.
- Studio lồng tiếng video AI & Gemini 1-Click BYOK.
- Công nghệ chụp OCR màn hình tam ngữ tối ưu (Tri-Lingual Screen OCR).
- Bộ nhận diện từ loại thông minh (Smart POS Detector).

---

## 💻 Yêu Cầu Hệ Thống

- **Hệ điều hành**: Windows 10 (64-bit) hoặc Windows 11 (64-bit).
- **Runtime**: Microsoft Edge WebView2 Evergreen Runtime (đã tích hợp sẵn trên Windows 10/11).
- **RAM**: Tối thiểu 2 GB (khuyến nghị 4 GB trở lên).
- **Dung lượng trống**: 300 MB.

---

## 📖 Hướng Dẫn Cài Đặt

1. Tải về tệp tin [**HyDict-v2.6.8-Setup.zip**](https://github.com/tahiep2012/HyDict-Releases/releases/download/v2.6.8/HyDict-v2.6.8-Setup.zip) hoặc [**HyDict-v2.6.8-Setup.exe**](https://github.com/tahiep2012/HyDict-Releases/releases/download/v2.6.8/HyDict-v2.6.8-Setup.exe).
2. Nhấp đúp vào tệp tin để mở trình cài đặt.
3. Giữ nguyên dấu tích chọn **`☑ Tạo shortcut ra màn hình desktop`** nếu bạn muốn có biểu tượng HyDict trên màn hình Desktop.
4. Nhấn **Cài đặt**. Quá trình cài đặt hoàn tất trong vài giây và ứng dụng sẽ tự động khởi động.

---

## 📞 Hỗ Trợ & Bản Quyền

- Tác giả: **Võ Tá Hiệp** ([@tahiep2012](https://github.com/tahiep2012))
- Dự án chính: [https://github.com/tahiep2012/HyDict](https://github.com/tahiep2012/HyDict)
