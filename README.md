# Not a Starboy 🎮🕹️⭐

Not a Starboy is motion and button controlled electronic pet built on the Seeed Studio XIAO ESP32-C3 and inspired by the hardware trends of the 1980s retro gaming era.

## Modifcations
While this project was inspired by the Half-life Week 1 Starter project, Starbie, I have made several modifications to make it my own:
* My PCB board has a custom layout and shape which mimics a classic handheld
* Rather than Cherry MX key switches, I used tactile push buttons with a smaller footprint
* My hardware design and firmware utilizes three buttons, instead of two

## Images of Hardware Design

<img width="775" height="507" alt="image" src="https://github.com/user-attachments/assets/aba2fa90-bc61-4de9-8081-77ecbc01c0f2" />

<img width="883" height="485" alt="image" src="https://github.com/user-attachments/assets/1c62ea72-6524-4d6e-a09d-a86435d07510" />

## Bill of Materials

| Reference | Qty | Value | Description / Notes |
| :--- | :---: | :--- | :--- |
| J1 | 1 | Conn_01x04_Socket | OLED Display connection |
| J3 | 1 | Conn_01x08_Pin | Expansion Header |
| R1 | 1 | 10K | Resistor |
| SW1, SW2, SW3 | 3 | SW_Push | Standard Tactile Buttons |
| U1 | 1 | DHT11 | Temperature/Humidity Sensor |
| U2 | 1 | XIAO-ESP32-C3-SMD | Microcontroller |

## Setup Instructions
1. Open the project in Arduino IDE or VS Code
2. Select the Seeed Studio XIAO-ESP32-C3
3. Installed required libraries (ex. Adafruit GFX Library, Adafruit SSD1306, Adafruit MPU6050 and DHT sensor library)
4. Flash the code to the PCB

## Gerber Files Location 
* All design files are located in this not_a_starboy_- repository.
