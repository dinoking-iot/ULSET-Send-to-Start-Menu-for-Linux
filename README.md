🚀 ULSET — "Send to Start Menu" for Linux (v2026.10.18_v16)

Công cụ đưa mọi file, thư mục và ứng dụng Windows (.exe) vào Start Menu Linux chỉ bằng một cú click chuột phải!
Tired of manually writing .desktop files just to launch portable Windows apps or local scripts from your Linux application menu? ULSET (Universal Linux Shortcut Environment Tool) automates the entire process cleanly, safely, and right from your file manager's context menu.

Chán ngấy việc phải tự gõ file .desktop thủ công chỉ để mở một ứng dụng Windows portable hay file script từ Start Menu trên Linux? ULSET tự động hóa toàn bộ quy trình này một cách gọn gàng, an toàn và tích hợp thẳng vào menu chuột phải của trình quản lý tệp.

✨ KEY FEATURES / TÍNH NĂNG NỔI BẬT

🖱️ One-Click Right-Click Integration / Tích hợp Chuột phải Tiện lợi

Right-click any file, folder, script (.sh), or Windows executable (.exe, .msi, .bat, .lnk) and select "Send to Start Menu" to create a native launcher immediately.
Chỉ cần chuột phải vào bất kỳ tệp, thư mục, script (.sh) hay chương trình Windows (.exe, .msi, .bat, .lnk) nào và chọn "Gửi vào Start Menu" để tạo lối tắt ngay lập tức.

🍷 Smart Wine & Icon Handling / Xử lý Wine & Icon Thông minh

Automatically extracts high-resolution icons directly from .exe files in the background without freezing your UI, and launches Windows apps using your existing Wine setup—plus built-in anti-cheat detection warnings for gamers.
Tự động trích xuất biểu tượng (icon) độ phân giải cao từ file .exe chạy ngầm mà không gây giật lag, khởi chạy ứng dụng qua Wine có sẵn trên máy—kèm tính năng cảnh báo sớm các tệp anti-cheat cho game thủ.

🛡️ 100% Safe & Non-Destructive / An toàn Tuyệt đối & Không Can thiệp Hệ thống
• Lives entirely inside your $HOME directory (~/.local/bin and ~/.local/share). No sudo changes to /etc, no systemd services, and no background autostart bloat.
• Chỉ hoạt động trong thư mục cá nhân ($HOME). Không sửa đổi /etc, không cài dịch vụ systemd và không tự khởi động ngầm gây nặng máy.

• Add-only dependency check: Installs only missing tools (wine, winetricks, icoutils, cabextract) using --needed / --no-upgrade, never touching or upgrading your existing system packages.
• Kiểm tra gói phụ thuộc theo cơ chế "chỉ bổ sung": Chỉ cài thêm công cụ còn thiếu, tuyệt đối không nâng cấp hay làm hỏng cấu hình BigLinux/Wine đang có.

📂 NTFS/exFAT Partition Friendly / Tương thích Tốt với Ổ đĩa Windows (NTFS/exFAT)

Smart binary inspection ensures documents (.docx, .xlsx, .pdf, .txt) stored on Windows partitions—where every file gets marked executable—open properly in your default app instead of throwing execution errors.
Cơ chế kiểm tra định dạng tệp thông minh giúp các tài liệu lưu trên phân vùng Windows (vốn bị gắn cờ thực thi) luôn mở đúng bằng ứng dụng mặc định thay vì báo lỗi chạy nhầm.

🖥️ Broad Distro & Desktop Support / Hỗ trợ Đa Nền tảng & Giao diện

Built with priority for BigLinux, and works seamlessly across Arch, Manjaro, Ubuntu, Debian, Mint, Zorin, Fedora, openSUSE and file managers like Dolphin, Nautilus, Nemo, Caja, Thunar, PCManFM.
Tối ưu ưu tiên cho BigLinux, đồng thời tương thích mượt mà với Arch, Manjaro, Ubuntu, Debian, Mint, Zorin, Fedora, openSUSE cùng các trình quản lý tệp phổ biến như Dolphin, Nautilus, Nemo, Caja, Thunar, PCManFM.

⚡ HOW TO USE / HƯỚNG DẪN SỬ DỤNG

1️⃣ Download & Run / Tải về & Chạy:

Double-click send_to_startmenu.sh from your file manager (it automatically opens a terminal) or run via CLI:
Nhấp đúp vào tệp send_to_startmenu.sh trong trình quản lý tệp (tự động mở cửa sổ dòng lệnh) hoặc chạy qua Terminal:
```bash
chmod +x send_to_startmenu.sh && ./send_to_startmenu.sh
```
2️⃣ Install / Cài đặt:

Choose option 1 (Install / Update) in the interactive menu, or run unattended with ./send_to_startmenu.sh --install --yes. An automatic self-test verifies everything works end-to-end.
Chọn phím 1 (Cài đặt / Cập nhật) trong menu tương tác, hoặc chạy nhanh bằng lệnh ./send_to_startmenu.sh --install --yes. Công cụ sẽ tự động chạy kiểm tra toàn diện để đảm bảo mọi thứ hoạt động trơn tru.

3️⃣ Clean Uninstall Anytime / Gỡ bỏ Sạch sẽ Bất cứ Lúc nào:

Need to remove it? Run ./send_to_startmenu.sh --uninstall to wipe all helpers and right-click menus while keeping your Wine setup intact.
Muốn gỡ bỏ? Chạy ./send_to_startmenu.sh --uninstall để xóa sạch các tệp hỗ trợ và menu chuột phải mà vẫn giữ nguyên vẹn môi trường Wine của bạn.
