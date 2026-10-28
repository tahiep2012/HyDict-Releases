# HyDict Desktop Releases 🚀

> **HyDict Desktop** — Ứng dụng từ điển thông minh đa ngôn ngữ (Tiếng Trung 🇨🇳, Tiếng Anh 🇬🇧, Tiếng Nhật 🇯🇵) chuyên sâu cho việc tra cứu tức thì, học tập thẻ ghi nhớ Anki, chụp OCR màn hình và lồng tiếng phụ đề video bằng AI trên hệ điều hành Windows.

---

## 📥 Tải Về Phiên Bản Mới Nhất: v2.6.9

| Gói Tải Về | Tệp Tin | Kích Thước | Mô Tả & Tính Năng |
| :--- | :--- | :--- | :--- |
| **Bản Cài Đặt ZIP (Khuyên Dùng)** | [**HyDict-v2.6.9-Setup.zip**](https://github.com/tahiep2012/HyDict-Releases/releases/download/v2.6.9/HyDict-v2.6.9-Setup.zip)<br>*(hoặc [HyDict-v2.6.9-Setup.exe](https://github.com/tahiep2012/HyDict-Releases/releases/download/v2.6.9/HyDict-v2.6.9-Setup.exe))* | `~45.5 MB` | • Trình cài đặt tự động đầy đủ tính năng đóng gói trong file nén .zip an toàn.<br>• **Có nút check tạo Shortcut ra màn hình Desktop (bật sẵn)**.<br>• Tự động kích hoạt gói OCR Tiếng Nhật Windows.<br>• Tự động tạo lối tắt trong Start Menu & tích hợp uninstaller.<br>• Đóng gói sẵn toàn bộ cơ sở dữ liệu từ điển offline. |
| **Bản Portable (Chạy Ngay)** | [**HyDict-v2.6.9-windows-x64.zip**](https://github.com/tahiep2012/HyDict-Releases/releases/download/v2.6.9/HyDict-v2.6.9-windows-x64.zip) | `~45.5 MB` | • Dành cho người dùng muốn giải nén là chạy ngay không cần cài đặt.<br>• Phù hợp lưu trữ trong USB hoặc môi trường di động. |

---

## ✨ Điểm Mới Nổi Bật Trong Phiên Bản v2.6.9

1. **Bộ Lọc Động Câu Ví Dụ Giản Thể & Phồn Thể Cho Từ Điển Tiếng Trung (Smart Script Filter)**:
   - **Khi chọn Giản thể**: Toàn bộ câu ví dụ có sẵn trong từ điển nếu có chứa bất kỳ ký tự chữ Hán Phồn thể đặc thù nào sẽ tự động **bị ẩn đi 100%**, chỉ hiển thị câu thuần Giản thể hoặc trung tính.
   - **Khi chọn Phồn thể**: Toàn bộ câu ví dụ có sẵn trong từ điển nếu có chứa bất kỳ ký tự chữ Hán Giản thể đặc thù nào sẽ tự động **bị ẩn đi 100%**, chỉ hiển thị câu thuần Phồn thể hoặc trung tính.
   - **Empty State thông minh**: Nếu từ vựng chưa có câu ví dụ khớp với thể chữ đã chọn trong cơ sở dữ liệu, giao diện hiển thị thông báo hướng dẫn trực quan để bấm nút **"Tạo câu ví dụ"** bằng AI (Gemini / Agnes AI) đúng chuẩn 100% thể chữ mong muốn.
   - **Đồng bộ thẻ Anki**: Thẻ gửi sang Anki luôn chuẩn xác theo thể chữ đang chọn (từ vựng Phồn thể đi kèm câu ví dụ Phồn thể).

2. **Cập Nhật Nhãn Phiên Bản Trực Quan (v2.6.9)**:
   - Hiển thị nhãn phiên bản `HyDict Desktop v2.6.9` rõ ràng ngay tại thanh điều hướng Cài đặt hệ thống.

3. **Kế Thừa Toàn Bộ Các Tính Năng Đỉnh Cao v2.6.8 & v2.6.7**:
   - Sửa triệt để lỗi kiểm tra trùng thẻ Anki (chỉ kiểm tra trường Sort Field/Word Field đầu tiên).
   - Tự động cài đặt AnkiConnect offline 100% (Zero-Configuration).
   - Tự động khởi chạy Anki Desktop khi thêm thẻ.
   - Pre-check trùng lặp tiết kiệm 100% token AI & thời gian sinh âm thanh.
   - Sinh ảnh minh họa AI đa ngôn ngữ (Trung - Anh - Nhật) theo phong cách đã chọn.
   - Khóa bản quyền theo phần cứng (Hardware Machine ID).

---

## 🌟 Nhật Ký Các Phiên Bản Trước

### Phiên Bản v2.6.8:
- Nút chuyển đổi tạo câu ví dụ Giản thể / Phồn thể AI chuyên biệt cho tiếng Trung.
- Sửa triệt để lỗi báo trùng thẻ Anki sai lệch (Exact Match Sort Field Gate).

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

---

## 💻 Yêu Cầu Hệ Thống

- **Hệ điều hành**: Windows 10 (64-bit) hoặc Windows 11 (64-bit).
- **Runtime**: Microsoft Edge WebView2 Evergreen Runtime (đã tích hợp sẵn trên Windows 10/11).
- **RAM**: Tối thiểu 2 GB (khuyến nghị 4 GB trở lên).
- **Dung lượng trống**: 300 MB.

---

## 📖 Hướng Dẫn Cài Đặt

1. Tải về tệp tin [**HyDict-v2.6.9-Setup.zip**](https://github.com/tahiep2012/HyDict-Releases/releases/download/v2.6.9/HyDict-v2.6.9-Setup.zip) hoặc [**HyDict-v2.6.9-Setup.exe**](https://github.com/tahiep2012/HyDict-Releases/releases/download/v2.6.9/HyDict-v2.6.9-Setup.exe).
2. Nhấp đúp vào tệp tin để mở trình cài đặt.
3. Giữ nguyên dấu tích chọn **`☑ Tạo shortcut ra màn hình desktop`** nếu bạn muốn có biểu tượng HyDict trên màn hình Desktop.
4. Nhấn **Cài đặt**. Quá trình cài đặt hoàn tất trong vài giây và ứng dụng sẽ tự động khởi động.

---

## 📞 Hỗ Trợ & Bản Quyền

- Tác giả: **Võ Tá Hiệp** ([@tahiep2012](https://github.com/tahiep2012))
- Dự án chính: [https://github.com/tahiep2012/HyDict](https://github.com/tahiep2012/HyDict)
