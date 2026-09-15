## Cấu hình

- STM32F103C6, nguồn 3.3 V, clock HSI mặc định.
- LED đỏ: PA5; LED vàng: PA6; LED xanh: PA7.
- LED active-low: GPIO RESET bật LED, GPIO SET tắt LED.

## Nội dung

- Đỏ sáng 5 giây → vàng sáng 2 giây → xanh sáng 3 giây, lặp liên tục.
- `SOURCE/`: project STM32CubeIDE Ex2.
- `PROTEUS/Ex2.pdsprj`: mạch mô phỏng.
- `FIRMWARE/Ex2.hex`: chương trình đã build để chạy mô phỏng.
