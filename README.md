# 🎨 Minecraft HEX Color Generator

![Phiên bản](https://img.shields.io/badge/phiên_bản-1.0.0-blue)
![Ngôn ngữ](https://img.shields.io/badge/HTML-CSS_JS-orange)
![Minecraft](https://img.shields.io/badge/Minecraft-1.16+-green)

Công cụ tạo mã màu HEX và gradient trực quan, mạnh mẽ dành cho máy chủ Minecraft. Dễ dàng tạo hiệu ứng văn bản đẹp mắt cho tên, lore vật phẩm, MOTD và nhiều hơn nữa.

Truy cập công cụ: **[MinhSoora Minecraft HEX Generator](https://your-project-link.com)** *(Thay bằng link thật của bạn)*

## ✨ Tính năng nổi bật

- 🎨 **Trình chỉnh sửa bảng màu trực quan**: Thêm, xóa, kéo thả để sắp xếp thứ tự màu sắc.
- 🌈 **Kho preset màu phong phú**: Hơn 18 bảng màu gradient được yêu thích (Cầu vồng, Lửa, Đại dương, Instagram, TikTok...).
- 📝 **Hỗ trợ nhiều chế độ**:
  - **Văn bản**: Tạo gradient cho tên, prefix, tin nhắn.
  - **Lore**: Tạo gradient cho nhiều dòng mô tả vật phẩm.
  - **MOTD**: Tạo gradient cho thông điệp chào mừng máy chủ.
- 🔧 **Đa dạng định dạng đầu ra**: Hỗ trợ hầu hết các plugin và nền tảng phổ biến.
  - `&#rrggbb` (Mặc định), `&x&r&r&g&g&b&b` (Legacy), `<#rrggbb>` (Chat)
  - `§x§r§r§g§g§b§b` (Console), `[COLOR=#rrggbb]` (BBCode)
  - **Adventure API**, **Iridium API**
  - Và nhiều định dạng khác...
- 🎬 **Tạo hoạt ảnh gradient**: Tự động sinh các khung hình để tạo hiệu ứng chuyển động cho tên.
- 🧬 **Giải mã gradient**: Trích xuất bảng màu từ bất kỳ mã gradient nào có sẵn.
- 💾 **Quản lý lịch sử**: Lưu lại các cấu hình màu yêu thích và tải lại nhanh chóng.
- ⚙️ **Xuất/Nhập cài đặt**: Dễ dàng chia sẻ hoặc sao lưu cấu hình.
- ✨ **Hiệu ứng phong cách Minecraft**: Font chữ Minecraft, hiệu ứng lấp lánh khi di chuột và hạt bay nền.

## 🖼️ Giao diện

![Minecraft HEX Generator Preview](screenshot.png) *(Bạn có thể thêm ảnh chụp màn hình ở đây)*

## 🚀 Hướng dẫn sử dụng

### 1. Chọn chế độ
Sử dụng các tab ở đầu để chuyển đổi giữa chế độ **Văn bản**, **Lore** và **MOTD**.

### 2. Nhập nội dung
- **Văn bản**: Nhập trực tiếp vào ô bên dưới bản xem trước.
- **Lore**: Nhập mỗi dòng lore trên một dòng mới.
- **MOTD**: Nhập tối đa 2 dòng cho thông điệp máy chủ.

### 3. Tùy chỉnh bảng màu
- **Thêm/Xóa màu**: Sử dụng nút `+` hoặc dấu `×` trên mỗi ô màu.
- **Đổi màu**: Click vào ô màu hoặc nhập trực tiếp mã HEX (6 ký tự).
- **Sắp xếp**: Kéo thả các ô màu để thay đổi thứ tự gradient.
- **Preset**: Chọn từ danh sách thả xuống để tải nhanh các bảng màu có sẵn.

### 4. Cấu hình và xuất mã
- Chọn **Định dạng plugin** phù hợp với máy chủ của bạn.
- Bật/Tắt các **kiểu chữ** (Đậm, Nghiêng, Gạch dưới, Gạch ngang).
- Mã kết quả sẽ hiển thị và tự động cập nhật trong khung **MÃ ĐẦU RA**.
- Nhấn **Sao chép mã** để sử dụng.

### 5. Tính năng nâng cao
- **🎬 Tạo hoạt ảnh**: Chọn hướng và nhấn "Tạo hoạt ảnh" để sinh các khung hình. Dán các khung hình này vào cấu hình plugin hỗ trợ animation.
- **🧬 Giải mã**: Dán một mã gradient bất kỳ vào mục "Giải mã gradient", điều chỉnh "ngưỡng" và nhấn "Giải mã & Tải" để tự động tái tạo bảng màu.
- **📚 Lịch sử**: Nhấn "Lưu vào lịch sử" để lưu cấu hình hiện tại và tải lại sau.

## 🛠️ Công nghệ sử dụng

- **HTML5**: Cấu trúc ứng dụng.
- **CSS3**: Thiết kế giao diện hiện đại, tối màu, responsive và các hiệu ứng.
- **JavaScript (ES6)**: Xử lý logic chính, gradient động, drag & drop, quản lý state.
- **Twemoji**: Hiển thị emoji nhất quán trên mọi nền tảng.
