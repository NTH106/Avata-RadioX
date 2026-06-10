# Avata-RadioX
<div align="center">

# 🚀 Avata RadioX

### Custom ExpressLRS Firmware for RC Systems

10 Channels • ESP32 • SX1280 • Telemetry • WiFi Update • UART

---

Avata RadioX là firmware tùy biến dựa trên nền tảng ExpressLRS, cung cấp kết nối điều khiển 10 kênh và khả năng mở rộng linh hoạt cho RC Car, RC Boat và các ứng dụng RC khác.

⭐ Nếu dự án hữu ích hãy Star repository để ủng hộ quá trình phát triển.

</div>

---

# 📖 Giới thiệu 

Avata RadioX là firmware được phát triển dựa trên nền tảng ExpressLRS dành cho các bộ phát (TX) và bộ thu (RX) sử dụng ESP32 và SX1280.

Dự án được xây dựng với mục tiêu:

* Hiệu năng cao
* Telemetry hai chiều
* Dễ dàng cấu hình
* Hỗ trợ cập nhật nhanh chóng
* Khả năng tùy biến cao

Firmware phù hợp cho:

* Fixed Wing
* RC Car
* RC Boat
* Các hệ thống điều khiển từ xa khác

---

# ✨ Tính năng

## 📡 Radio Link

* Hỗ trợ ExpressLRS 2.4GHz
* Độ trễ thấp
* Kết nối ổn định
* Telemetry hai chiều
* Link Quality Monitoring
* RSSI Monitoring
* Dynamic Packet Handling

## 🎮 Channel Support

* 10 Kênh điều khiển
* Hỗ trợ CRSF
* Hỗ trợ UART
* Dễ dàng mở rộng

## 🌐 WiFi Features

* WiFi Configuration
* Firmware Update
* WebUI Management

## 🔧 System Features

* Binding Phrase
* Auto Reconnect
* Failsafe Protection
* Telemetry Monitoring
* Remote Update

---

# ⚙️ Thông số kỹ thuật

| Thành phần  | Thông tin         |
| ----------- | ----------------- |
| MCU         | ESP32             |
| RF Chip     | SX1280            |
| Protocol    | ExpressLRS 2.4GHz |
| Channels    | 10CH              |
| Telemetry   | Supported         |
| WiFi Update | Supported         |
| UART Update | Supported         |

---

# 📦 Firmware Releases

| Firmware                       | Chức năng |
| ------------------------------ | --------- |
| Avata RadioX 10ch UART.bin     | RX UART   |
| Avata RadioX 10ch WIFI.bin     | RX WiFi   |
| Avata RadioX TX 500mW UART.bin | TX UART   |
| Avata RadioX TX 500mW WIFI.bin | TX WiFi   |

---

# 🚀 Hướng dẫn nạp Firmware

## Nạp qua UART ( áp dụng đối với esp đã xóa bộ nhớ EEPROM hoặc esp mới )

Firmware có thể được nạp trực tiếp bằng trình duyệt thông qua ESP Web Tool.

### Bước 1

Kết nối thiết bị với máy tính bằng cáp USB TTL.

### Bước 2

Mở công cụ:

https://esptool.spacehuhn.com/

### Bước 3

Nhấn **Connect**

### Bước 4

Chọn đúng cổng COM của thiết bị.

### Bước 5

Nhấn **Add File**

### Bước 6

Chọn file firmware phù hợp.

### Bước 7

Thiết lập địa chỉ flash:

0x0000

### Bước 8

Nhấn **Program**

### Bước 9

Chờ quá trình nạp hoàn tất.

### Bước 10

Khởi động lại thiết bị.

---

# 🌐 Cập nhật qua WiFi

1. Khởi động thiết bị.
2. Kết nối tới WiFi do thiết bị phát ra.
3. Truy cập:

http://10.0.0.1

4. Đổi tên firmware đã tải về thành firmware.bin
5. Chọn Firmware Update
6. Upload firmware mới.
7. Chờ thiết bị khởi động lại.

---

# 📊 Telemetry

Firmware hỗ trợ:

* RSSI
* LQ
* RF Mode
* TX Power
* Packet Statistics
* Voltage Sensor
* Telemetry Return

---

# ✅ Kiểm tra hoạt động

Sau khi nạp thành công:

* Thiết bị khởi động bình thường.
* Có thể truy cập WebUI.
* TX và RX kết nối thành công.
* Hiển thị Telemetry Connected.
* Các kênh điều khiển hoạt động chính xác.
* Link Quality ổn định.

---

# ❓ FAQ

## Không thể Bind TX và RX?

Kiểm tra:

* Binding Phrase
* Firmware Version
* Antenna
* Nguồn cấp

---

## Không có Telemetry?

Kiểm tra:

* UART Configuration
* Radio Configuration
* Firmware Compatibility

---

## Không truy cập được WebUI?

Thử:

* Khởi động lại thiết bị
* Kết nối lại WiFi
* Xóa cache trình duyệt
* Nạp lại firmware

---

## RSSI thấp?

Nguyên nhân thường gặp:

* Antenna lỏng
* Antenna hỏng
* Nhiễu RF
* Công suất phát thấp

---

# 🛣 Roadmap

## Hoàn thành

* [x] 10CH Support
* [x] UART Firmware
* [x] WiFi Firmware
* [x] Telemetry
* [x] 500mW TX Support

---

# 🤝 Đóng góp

Mọi đóng góp đều được hoan nghênh.

1. Fork repository.
2. Tạo branch mới.
3. Commit thay đổi.
4. Push lên repository.
5. Tạo Pull Request.

---

# 📝 Giấy phép

Dự án được phát hành theo giấy phép MIT.

Bạn có thể tự do sử dụng, chỉnh sửa và phát triển dựa trên mã nguồn của dự án.

---

# 👨‍💻 Tác giả

### NH06

Project: Avata RadioX

---

<div align="center">

### ⭐ Star Repository nếu dự án hữu ích

Cảm ơn bạn đã sử dụng Avata RadioX.

</div>
