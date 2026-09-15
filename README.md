# Lab 1 - Exercise 1

Điều khiển LED đỏ và LED vàng sáng luân phiên, mỗi trạng thái kéo dài 2 giây.

## Cấu hình

- STM32F103C6, nguồn 3.3 V, clock HSI mặc định.
- LED đỏ: PA5; LED vàng: PA6.
- LED active-low: GPIO RESET bật LED, GPIO SET tắt LED.

## Nội dung

- `SOURCE/`: project STM32CubeIDE Ex1.
- `PROTEUS/Ex1.pdsprj`: mạch mô phỏng.
- `FIRMWARE/Ex1.hex`: chương trình đã build để chạy mô phỏng.

## Chạy mô phỏng

1. Tải hoặc clone repo và chuyển sang nhánh `Ex1`.
2. Mở `PROTEUS/Ex1.pdsprj` trong Proteus.
3. Nhấp đúp STM32, chọn lại Program File đến `FIRMWARE/Ex1.hex` trên máy của bạn (đường dẫn lưu trong mạch có thể là đường dẫn máy tác giả).
4. Chạy mô phỏng: đỏ sáng/vàng tắt 2 giây, rồi đỏ tắt/vàng sáng 2 giây; lặp lại.

## Build source

Trong STM32CubeIDE, chọn File → Import → General → Existing Projects into Workspace, chọn thư mục `SOURCE`, import project Ex1 rồi Build Project.
