# CFC (Curiosity's Flight Controller)

### About

This is a flight controller with USB-C, a Micro-SD card reader, a battery charger, servos, a pressure sensor, a IMU, a GNSS Module and voltage sensing via ADC. It was originally designed for model rockets but it can be used for planes too. I took inspiration from the @NotARoomba SFC guide, but designed it myself and this is my own creation.

### INSPIRATION:

This is my second project and first stasis project. Since I want to follow aerospace engineering, i chose to build a flight controller. I followed the @NotARoomba guide and built it from scratch. I added a GNSS Module for auto pilot and Voltage Sensing via ADC to know when the battery is getting low. I want to use this in my custom built RC plane. I really liked building everything although some things were a real pain.

### CHALLENGES:

My biggest challenge was routing the PCB, when I routed it for the first time the board was way too big to fit on the plane and way too expensive. So after that I significantly reduced the board size and made it the smallest it can get and the cheapest. In between that, I had to change a lot of pins and inputs in STM32CubeMX so that the routing wouldn't be an absolute mess, and that took a really long time and absolutely drained my patience and mental power.

### BOM:
| Name            | Purpose                      | Cost (USD) | Qty | Total (USD) | Link                         | Distributor |
|-----------------|-----------------------------|------------|-----|-------------|------------------------------|-------------|
| PCBA (1 board)  | The actual flight controller | $140       | 1   | $140        | https://www.elecrow.com/     | Elecrow     |

Total estimated cost: $140

### Extras:

This project does not need a case or anything 3D printed or designed, it will be inside a RC plane.
If you have any questions, DM me on slack: Mateus (mateus.flecha808)

## Schematic

### USB-C & Crystals
<img width="1388" height="570" alt="{BE57653B-7D3A-48C3-BE49-C0519F7B529C}" src="https://github.com/user-attachments/assets/1da0e030-423a-480b-a576-fc154799143a" />



### Decoupling, Buttons & Servos
<img width="1376" height="494" alt="{79CEA256-14AA-4DC2-861F-85EBC9C6EA1F}" src="https://github.com/user-attachments/assets/1f37d58d-0b92-4a44-a59d-2ae14f657380" />



### Battery Charger & STM32
<img width="1315" height="693" alt="{32F101CB-92D8-42CC-A244-E05E275E72F9}" src="https://github.com/user-attachments/assets/ec1ec9c6-ad06-4e2d-b7f1-e5b083789234" />



### Pressure Sensor & Micro-SD
<img width="1094" height="845" alt="{E111CCD5-0065-440A-B6FF-7CA9D5AE25CE}" src="https://github.com/user-attachments/assets/baf464b8-a617-49d6-afee-a1639f27c354" />



### Power & GNSS
<img width="1464" height="755" alt="{53D61D9F-42BA-49DF-AC49-1D3BC913D2A1}" src="https://github.com/user-attachments/assets/c55b7fd1-a668-4566-a529-544e49248656" />



### IMU
<img width="959" height="534" alt="{816D461F-DD70-45E3-AB0F-E9185D550F2D}" src="https://github.com/user-attachments/assets/c5f9f438-0214-4ac5-8a78-8cefe2874965" />



### All
<img width="1090" height="923" alt="{09707E38-BBC4-4B8D-BA47-B80D99204EBA}" src="https://github.com/user-attachments/assets/107af883-df5c-4bac-897c-e75a488d4c4c" />


---

## PCB
<img width="1004" height="905" alt="image" src="https://github.com/user-attachments/assets/edabb760-1594-4e6f-8d29-cd7476ebd0cc" />
