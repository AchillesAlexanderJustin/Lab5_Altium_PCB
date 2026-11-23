# Lab 5 - Altium Designer PCB

Nhóm 02 - Electronic Device Component Lab

| File | Nội dung |
|---|---|
| Lab5_4.1_LED_2_mau_Project.zip | Project Altium bài 4.1 - mạch LED 2 màu |
| Lab5_4.1_LED_2_mau_Gerber.zip | File Gerber bài 4.1 |
| Lab5_4.2_Relay_Project.zip | Project Altium bài 4.2 - mạch Relay |
| Lab5_4.2_Relay_Gerber.zip | File Gerber bài 4.2 |

## Cập nhật 23/11/2026 – bài 4.2 Relay

- Đổ đồng GND kín cả board, **cả 2 mặt** (GND_L01_P000 mặt Top, GND_L02_P001 mặt Bottom).
- Dời chữ RL1, P1 lên Y = 1275 mil để hết lỗi Silk to Silk.
- DRC (23/11 15:40): **Violations Detected: 0**. Báo cáo kèm trong project zip.
- Xuất lại Gerber + NC Drill lúc 15:46 ngày 23/11 (bản cũ ngày 20/11 thiếu đồng mặt Top).
- Bỏ tham chiếu CAMtastic1.Cam, CAMtastic2.Cam khỏi file .PrjPcb trong zip.
- Board 4.2: 75,57 × 20,83 mm.

## Cập nhật 23/11/2026 – bài 4.1 LED 2 màu

- Dời chữ R5 lên Y = 555 mil để hết lỗi lụa.
- DRC (23/11 15:51): **Violations Detected: 0**. Báo cáo kèm trong project zip.
- Đồng GND cả 2 mặt (GND_L01_P000 Top, GND_L02_P002 Bottom).
- Xuất lại Gerber + NC Drill lúc 15:52 ngày 23/11.
- Bỏ tham chiếu 4.1.Cam, 4.2.Cam khỏi file .PrjPcb trong zip.
- Board 4.1: 26,67 × 20,32 mm.
