# Nhóm_9_DTMT01
Cài đặt phần mềm ,công cụ lập trình cho STM32F1 và Blinking LED
# Bài tập LED + Nút nhấn

## Mô tả
- **Tiến trình 1**: 2 LED cấu hình ở chế độ Output, nhấp nháy với chu kỳ 1000ms.  
- **Tiến trình 2**: 1 LED (Output) + 1 nút nhấn (Input). LED đổi trạng thái mỗi lần người dùng nhấn nút.

## Phần cứng
- STM32  
- 3 LED + 3 điện trở hạn dòng (220Ω).  
- 1 nút nhấn 
- Dây cắm 
## Tiến trình 1
* Sơ đồ chân
- LED1: PA0  
- LED2: PA1  
## Tiến trình 2
* Sơ đồ chân
-LED: PA0
-Button: PA1
## Quan sát:
* Tiến trình 1
   - LED1 và LED2 nhấp nháy mỗi 1 giây.
* Tiến trình 2
   - LED sáng tắt tuỳ theo lần nhấn nút
   - Button khi bạn nhấn nút lần 1 LED sáng nhấn nút lần 2 LED tắt delay mỗi lần nhấn để led đổi chế độ 20ms.
