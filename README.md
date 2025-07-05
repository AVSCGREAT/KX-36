
---

# KX-36: BLDC RC Off-Road RWD Racecar
Designed and Built by AVSC

---

## Overview:

KX-36 is a rear-wheel-drive, off-road RC car powered by 2x 1000KV A2212 drone motors using a single GT2 belt system. It’s completely 3D printed – every component, from the steering knuckles to the chassis spine, was made to fit a standard 220x220mm bed. The goal? No glue, no epoxy, no weird slicing. Just bolts, nuts, and a lot of plastic.

The design is modular, overbuilt, and intentionally fun.

**Inspo/Ref. for my project**


![453310755-0431e8d6-eb49-4d44-b7cb-2c4b8c5e1d01-removebg-preview](https://github.com/user-attachments/assets/89af0f78-43d7-413d-b778-d0ff10778662)


**Inspired by 'Bujji' from movie "KALKI 2898"**


![unnamed 4](https://github.com/user-attachments/assets/31dc5ff0-5aa1-4e0c-97ce-e81dd88f7876)


### Assembled - 


![t725](https://github.com/user-attachments/assets/143fd634-8fcf-47b4-a90a-ccd8b17d670a)


**Assembled Onshape link**- [https://cad.onshape.com/documents/36c5373b89824f2c3393e501/w/0f491b5238d02f75787e74f6/e/eece62a6272dec732a0d6745?renderMode=0&uiState=686151a81646844f92666930
](url)

---

## Specs:

Drive Type: Rear-Wheel Drive (RWD), GT2 Belt
Motors: 2x A2212 1000KV Brushless
Chassis: 3D Printed, Modular Spine
Steering: Ackermann-inspired, MG996R Servo
Suspension: Rear Pivot Pod (Passive)
Battery Mount: Low-Center Tray
Control: 2x 30A ESCs, RC RX/TX
Build Style: Snap and Screw (M3)
Printer Volume: 220x220mm compatible

---

## Bill of Materials:

### Printed Parts (PLA or PETG):

* Rear Pod and Motor Mount
* Front Steering Axle
* Chassis Spine 
* Wheel Hubs and Knuckles
* Wire Management Clips

###  **Electronics**

| Item                                | Qty   | Est. Price (USD) | Total       |
| ---------------------------------- | ----- | ---------------- | ----------- |
| A2212 1000KV BLDC Motor            | 2     | $5.50 each      | **$11.00**  - https://robu.in/product/a2212-13t-1000kv-brushless-motor-outrunner-30a-esc/|
| 30A ESC with BEC                   | 2     | $6.00 each      | **$12.00** - https://robu.in/product/a2212-13t-1000kv-brushless-motor-outrunner-30a-esc/ |
| MG996R Servo                      | 1     | $5.00           | **$5.00**  - https://robu.in/product/towerpro-mg996r-digital-high-torque-servo-motor/ |
| 3CH/4CH TX+RX Set (FlySky i6-style)| 1    | $52.00          | **$52.00** - https://robu.in/product/flysky-fs-i6-2-4g-6ch-ppm-rc-transmitter-with-fs-ia6b-receiver/ |
| 3S 2200mAh LiPo Battery            | 1     | $22.00          | **$22.00** - https://robu.in/product/bonka-11-1v-2200mah-25c-3s-lithium-polymer-battery-pack/  |
| Connectors, UBEC, Wires            | 1 set | $3.00           | **$3.00**   |

**Subtotal: ~$63.00**

---

###  **Mechanical / Drivetrain**

| Item                      | Qty      | Est. Price (USD) | Total       |
| ------------------------- | -------- | ---------------- | ----------- |
| GT2 20T Pulleys           | 1        | $4.00 each      | **$4.00**  - https://www.amazon.in/Serplex%C2%AE-Synchronous-Aluminum-Projects-Printer/dp/B0D89W19JT/ref=sr_1_2_sspa?crid=2T854E0ZNRNWW&dib=eyJ2IjoiMSJ9.u88eXvTgeOqZGxd5AzAoeGqZoljqAZPa7752MQWVPWnECsXUpA7v5Eie-r47skFN1ATacee6QyhiOaie0LRN_qz85ZpyQ_rn3zGloQ_I6t8kenQ8QTx3Cner31DNNjzaj-ph8fhKtdfwARwrg7M8ylaxdlxlzM2L8z_t3EsH6h9fjQ4kA5K6Qj0WIK84n6R-YoK7SOFfC4cSyDyaKJ3t-Ae9-xdtr-CRBp-ZP-6WJeYWSPP0yonLAnpnQKVhvUcX6JNIeq-kCvTDwfpJNHHcVsGoG8xD2oLyRPqF8saQjTk.Fh38liv-NsS5fPczEuU_Vck_cBLG9CY2_TcJOrOQXCk&dib_tag=se&keywords=gt2+20t+pulley&qid=1751690070&sprefix=gt2+20%2Caps%2C273&sr=8-2-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1 |
| GT2 60T Pulleys           | 1        | $6.00 each      | **$6.00**   - https://www.amazon.in/Serplex%C2%AE-Synchronous-Aluminum-Projects-Printer/dp/B0D89W19JT/ref=sr_1_2_sspa?crid=2T854E0ZNRNWW&dib=eyJ2IjoiMSJ9.u88eXvTgeOqZGxd5AzAoeGqZoljqAZPa7752MQWVPWnECsXUpA7v5Eie-r47skFN1ATacee6QyhiOaie0LRN_qz85ZpyQ_rn3zGloQ_I6t8kenQ8QTx3Cner31DNNjzaj-ph8fhKtdfwARwrg7M8ylaxdlxlzM2L8z_t3EsH6h9fjQ4kA5K6Qj0WIK84n6R-YoK7SOFfC4cSyDyaKJ3t-Ae9-xdtr-CRBp-ZP-6WJeYWSPP0yonLAnpnQKVhvUcX6JNIeq-kCvTDwfpJNHHcVsGoG8xD2oLyRPqF8saQjTk.Fh38liv-NsS5fPczEuU_Vck_cBLG9CY2_TcJOrOQXCk&dib_tag=se&keywords=gt2+20t+pulley&qid=1751690070&sprefix=gt2+20%2Caps%2C273&sr=8-2-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1|
| GT2 Belt                  | 1        | $1.50           | **$1.50**   -https://www.amazon.in/Serplex%C2%AE-Synchronous-Aluminum-Projects-Printer/dp/B0D89W19JT/ref=sr_1_2_sspa?crid=2T854E0ZNRNWW&dib=eyJ2IjoiMSJ9.u88eXvTgeOqZGxd5AzAoeGqZoljqAZPa7752MQWVPWnECsXUpA7v5Eie-r47skFN1ATacee6QyhiOaie0LRN_qz85ZpyQ_rn3zGloQ_I6t8kenQ8QTx3Cner31DNNjzaj-ph8fhKtdfwARwrg7M8ylaxdlxlzM2L8z_t3EsH6h9fjQ4kA5K6Qj0WIK84n6R-YoK7SOFfC4cSyDyaKJ3t-Ae9-xdtr-CRBp-ZP-6WJeYWSPP0yonLAnpnQKVhvUcX6JNIeq-kCvTDwfpJNHHcVsGoG8xD2oLyRPqF8saQjTk.Fh38liv-NsS5fPczEuU_Vck_cBLG9CY2_TcJOrOQXCk&dib_tag=se&keywords=gt2+20t+pulley&qid=1751690070&sprefix=gt2+20%2Caps%2C273&sr=8-2-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1|
| 5mm Steel Shaft           | 1        | $1.30           | **$1.30**   |
| 3mm Steel Rod             | 1        | $1.50           | **$1.50**   |
| Bearings (5×11×4mm)       | 6        | $0.25 each      | **$1.50**   |
| M3 Screws, Inserts, Nuts  | Assorted | $3.00           | **$3.00**  - https://www.amazon.in/sspa/click?ie=UTF8&spc=MTo4NDM2MzExNzEzMzAxMjM4OjE3NTE2OTAxMTQ6c3BfYXRmOjMwMDE0MzE4MjM2OTkzMjo6MDo6&url=%2FEpi-Torque-Epic-Torque-Doityourself-Assortment%2Fdp%2FB08F4K55T2%2Fref%3Dsr_1_2_sspa%3Fcrid%3D960F4QASPQNT%26dib%3DeyJ2IjoiMSJ9.77zWTzKNb3lk4whLwiyGnWpgXnT4JMB4oV2Y93Yik4bA1MO8RtvKv07ybqmUHAFYNA1UYfalkcE3Iuhh06MHZxwzGdGxJd19EvwClAPV1Is8Npw90uXValqReDmO2viy8rekDcOKPWjEs1wD4DAVTVqkXBQL24zTkk8GeZaqVzm1L52cOnhuOUaNvjnioSMuSRcR7PTsKtdhftv7YNCFcBTvYNCc-DC347ZxTRy23nouKvWGfb0PT-3ykiCFIYArG8AT3LYfm31yGex_MYlQo7_ebvJIPgONCRzXXtL0FaI.QzQMZuacGbRqH5lULSLKGmXaS8FF7afs5EU2VrxFxpk%26dib_tag%3Dse%26keywords%3Dm4%2Bnuts%26qid%3D1751690114%26sprefix%3Dm4%2Bnut%252Caps%252C274%26sr%3D8-2-spons%26sp_csd%3Dd2lkZ2V0TmFtZT1zcF9hdGY%26psc%3D1&cr=DUB  |
| RC Off-road Wheels        | 4        | $3.00 each      | **$12.00**  -https://robu.in/product/65mm-robot-smart-car-12-rim-wheel-blue/  |
| Shock Absorbers           | 2        | $4.50 each      | **$9.00**  - https://robu.in/product/wltoys-a959-aluminum-shock-absorber-1-pair/ |


**Subtotal: ~$45.00**


---

###  **Total Estimated Cost**

| Category                    | Price                 |
| --------------------------- | --------------------- |
| **Electronics**             | **$63.00**            |
| **Mechanical / Drivetrain** | **$45.00**   |
| **Tools & Misc**            | **$12.00**            |

## Total: $120.00 – $125.00 USD

---

---

<img width="919" alt="image" src="https://github.com/user-attachments/assets/bcc81950-2d82-41cf-a9cb-286526a27363" />


---

## Development Log:

Day 1 – Concept Dump

Day 2 – Rear Drivetrain Module

Day 3 – Front Steering System

Day 4 – Chassis Spine

Day 5 – Rear Articulation

Day 6 – Full Assembly in CAD

Day 7 – Print Prep

---

### File Structure (for organization):

KX-36

* STLs
* Final BOM
* README.txt (this file)
* JOURNAL.md

---

### Printing Tips:

Material: PETG
Layer Height: 0.2mm
Infill: 40–60% for strength
Supports: Minimal or none needed
Brim: Recommended for tall or thin parts
Print Volume: All fits in 220x220mm bed

---

## Project Status:

CAD work is complete. All STL files are ready and prepped.
Waiting for hardware to arrive:

* 2x A2212 1000KV Motors
* 1x GT2 Pulley Kit
* 2x 30A ESCs
* 1x Receiver and Transmitter

Printing will start as soon as parts arrive. Fingers crossed it drives and doesn’t catch fire.

---

### Future Plans:

* Replace dummy shocks with real dampers (Wltoys Aluminum ones)
* Add TPU tires or hybrid print rubbers
* Add telemetry (speed, temp) via Arduino or Pi
* FPV camera for POV racing
* Optional 4WD version with extra motors

---

### Tools Used:

| Onshape – 3D modeling
| 3ding – 3d Print service
| TinkerCAD – Early sketches
| Github – README editing

---

### Credits:

Project by AVSC (Hack Club Highway Grant project)
Big thanks to junk drawer electronics, patience, and Ctrl+Z

---

### Contact:

Want to remix, collab, or get help building your own version?
Reach out on GitHub @AVSCGREAT or through Hack Club Slack @AVSC.

---

