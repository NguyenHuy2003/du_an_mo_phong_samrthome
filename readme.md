# MÔ PHỎNG SMART HOME - PLATFORMIO - VS CODE

## Giới thiệu

Dự án này là một ứng dụng IoT sử dụng ESP32 để thu thập dữ liệu từ các cảm biến và điều khiển các thiết bị khác nhau thông qua Firebase. Dự án bao gồm việc đọc dữ liệu nhiệt độ, độ ẩm và khoảng cách, điều khiển một motor servo và các đèn LED dựa trên dữ liệu thu thập và lệnh từ Firebase.

## Yêu cầu

```plaintext
- ESP32 Development Board
- Cảm biến nhiệt độ và độ ẩm DHT22
- Cảm biến siêu âm HC-SR04
- Motor servo
- LED và các resistor phù hợp
- Cáp kết nối và các phụ kiện điện tử khác
- Môi trường VS Code
- IDE PlatformIO
- Wokwi
- Firebase account và các thông tin xác thự
```

## Cài đặt

```plaintext
1. Cài Wokwi trên VS Code.
2. Cài đặt IDE PlatformIO trên VS Code.
3. Sao chép mã nguồn từ repository này.
4. Cấu hình thông số kết nối WiFi và thông tin xác thực Firebase trong file `main.cpp`:
    - Đường dẫn đến Readtime Database.
    - Web API Key.
```

## Chạy trong VS Code

```plaintext
1. Mở project
2. F1 -> PlatformIO: Build
3. F1 -> Wokwi: Start Simulator 
```

## Sử dụng

```plaintext
- Khi ESP32 được kết nối thành công với mạng WiFi, nó sẽ bắt đầu thu thập dữ liệu từ các cảm biến và gửi chúng đến Firebase.
- Bạn có thể kiểm soát trạng thái của motor servo và các LED thông qua Firebase Console.
- Xem dữ liệu thu thập từ các cảm biến và trạng thái của các thiết bị điều khiển trong Firebase Realtime Database.
```

## Tích hợp Firebase

```plaintext
- Sử dụng Firebase để lưu trữ dữ liệu từ các cảm biến và điều khiển thiết bị.
- Đảm bảo rằng bạn đã cung cấp thông tin xác thực Firebase đúng và được bảo mật trong mã nguồn.
- Sử dụng Firebase Realtime Database để theo dõi dữ liệu và điều khiển thiết bị từ bất kỳ nơi nào.
```

## Tác giả

Được phát triển bởi [Nguyễn Văn Huy - 2121050061 - DCCTCLC66A1](https://github.com/NguyenHuy2003).
