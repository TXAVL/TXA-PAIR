# TXA Pair

**Tiếng Việt** · [English](#english)

Điều khiển và dọn dẹp điện thoại Android qua **ADB Wi-Fi** ngay trên chính điện thoại, **không cần cáp, không cần máy tính, không cần root**.

[**Tải bản mới nhất**](https://github.com/TXAVL/TXA-PAIR/releases/latest) · Android 11 trở lên

## Làm được gì

- **Kết nối ADB Wi-Fi cho chính máy này**: làm theo các bước ngay trên Trang chủ, nhập mã 6 số, xong. Lần sau app tự nối lại.
- **Điều khiển máy khác cùng Wi-Fi**: thêm máy bằng mã QR hoặc mã ghép nối, lưu lại để chuyển qua lại giữa các máy.
- **Điều khiển màn hình từ xa**: xem hình máy kia, chạm, giữ, vuốt, bấm Quay lại / Màn chính / Đa nhiệm, gõ chữ. Chế độ **Mượt** tới 60 khung/giây, có chế độ **Ảnh chụp** dự phòng.
- **Quản lý ứng dụng**: xem, tắt, gỡ, xóa cache, sao lưu APK và khôi phục app đã gỡ. Mỗi app có nhãn cho biết mức độ nên gỡ (Dọn thoải mái, Thận trọng, Dân chuyên, Vùng cấm) và thuộc nhóm nào (của hãng, lõi Android, nhà mạng, Google, linh tinh).
- **Công cụ**: dọn RAM và cache, đổi tần số quét, tăng tốc hoạt ảnh, Doze, khởi động lại, chỉnh cài đặt hệ thống có giải thích từng mục, kịch bản nhiều bước.
- **Tăng tốc game**: chọn game, bật các tinh chỉnh hiệu năng, khôi phục lại bằng một chạm.
- **Shell**: dòng lệnh cục bộ, qua ADB hoặc root, có mã thoát và nút dừng.
- **Giao diện**: tiếng Việt và English, cỡ chữ theo hệ thống hoặc tự chỉnh, sáng / tối.

## Cài đặt

1. Vào [Releases](https://github.com/TXAVL/TXA-PAIR/releases/latest) và tải file `.apk`.
2. Mở file, cho phép trình duyệt hoặc trình quản lý tệp cài ứng dụng khi hệ thống hỏi.
3. Mở TXA Pair và làm theo các bước trên Trang chủ: cấp thông báo, bật **Tùy chọn nhà phát triển**, bật **Gỡ lỗi không dây**, rồi nhập mã ghép nối.

Cần giúp thì vào **Cài đặt → Trợ giúp** trong app.

## Cập nhật

App tự kiểm tra bản mới ở nền và báo bằng thông báo kèm nội dung thay đổi. Bấm vào thông báo, chọn **Tải và cài đặt**. Lần đầu bạn cần cho phép TXA Pair cài ứng dụng trong trang cài đặt hệ thống.

## Quyền riêng tư

TXA Pair chạy cục bộ trên máy bạn. Không có tài khoản, không quảng cáo, không gửi dữ liệu hay danh sách ứng dụng đi đâu. Khóa ghép nối ADB được tạo và lưu riêng trong app. App chỉ truy cập Internet để kiểm tra bản cập nhật.

## Lưu ý

Gỡ hoặc tắt ứng dụng và đổi cài đặt hệ thống có thể làm máy hoạt động sai. Hãy đọc cảnh báo trong app và sao lưu trước khi thao tác.

## Ghi công

- [scrcpy](https://github.com/Genymobile/scrcpy) (Genymobile, Apache-2.0): máy chủ hình dùng cho chế độ điều khiển màn hình Mượt.
- Danh sách gỡ ứng dụng dựa trên [Universal Android Debloater Next Generation](https://github.com/Universal-Debloater-Alliance/universal-android-debloater-next-generation) (GPL-3.0).
- [libadb-android](https://github.com/MuntashirAkon/libadb-android) của Muntashir Al-Islam.

## Liên hệ

TXA Studio · [Facebook](https://fb.com/vlog.txa.2311) · [GitHub](https://github.com/TXAVL)

---

## English

Control and clean up an Android phone over **ADB Wi-Fi** from the phone itself: **no cable, no computer, no root**.

[**Download the latest release**](https://github.com/TXAVL/TXA-PAIR/releases/latest) · Android 11 or later

### What it does

- **ADB Wi-Fi for this phone**: follow the steps on Home, type the 6-digit code, done. It reconnects by itself next time.
- **Control another phone on the same Wi-Fi**: add it with a QR code or pairing code, and switch between saved phones.
- **Remote screen control**: see the other screen, tap, hold, swipe, press Back / Home / Recents, and type. **Smooth** mode runs up to 60 fps, with a **Snapshot** fallback.
- **App manager**: view, disable, remove, clear cache, back up APKs and restore removed apps. Each app carries a label for how safe it is to remove (Clean sweep, Handle with care, Experts only, Danger zone) and its group (maker apps, Android core, carrier, Google, misc).
- **Tools**: clean RAM and cache, change refresh rate, speed up animations, Doze, reboot options, a system settings editor that explains each key, and multi-step scripts.
- **Game boost**: pick a game, switch on performance tweaks, restore with one tap.
- **Shell**: local, ADB or root command line with exit codes and a stop button.
- **Interface**: Vietnamese and English, text size from the system or custom, light / dark.

### Install

1. Open [Releases](https://github.com/TXAVL/TXA-PAIR/releases/latest) and download the `.apk`.
2. Open it and allow your browser or file manager to install apps when asked.
3. Open TXA Pair and follow the steps on Home: allow notifications, turn on **Developer options**, turn on **Wireless debugging**, then enter the pairing code.

Need help? Open **Settings → Help** in the app.

### Updates

The app checks for new versions in the background and notifies you with what changed. Tap the notification and choose **Download and install**. The first time, allow TXA Pair to install apps in the system settings page.

### Privacy

TXA Pair runs locally on your phone. No accounts, no ads, and no data or app list is sent anywhere. The ADB pairing key is created and kept privately inside the app. The app only uses the Internet to check for updates.

### Caution

Removing or disabling apps and changing system settings can make a phone misbehave. Read the in-app warnings and back up before you act.

### Credits

- [scrcpy](https://github.com/Genymobile/scrcpy) (Genymobile, Apache-2.0): the video server behind Smooth screen control.
- The app removal lists are based on [Universal Android Debloater Next Generation](https://github.com/Universal-Debloater-Alliance/universal-android-debloater-next-generation) (GPL-3.0).
- [libadb-android](https://github.com/MuntashirAkon/libadb-android) by Muntashir Al-Islam.

### Contact

TXA Studio · [Facebook](https://fb.com/vlog.txa.2311) · [GitHub](https://github.com/TXAVL)
