# Phantom_OS
Official Phantom OS repository.
PHANTOM OS

PHANTOM OS is a simple firmware for the ESP32-C3 SuperMini.

It provides a small OLED interface with IR sending, WiFi tools, LittleFS storage and a local WebUI for uploading IR files.

HARDWARE

- ESP32-C3 SuperMini
- 0.96" 128x64 SSD1306 OLED
- 940nm IR transmitter
- 4 buttons

PINOUT

UP       = GPIO2
DOWN     = GPIO3
OK       = GPIO4
BACK     = GPIO5
IR TX    = GPIO6
OLED SDA = GPIO8
OLED SCL = GPIO9

FEATURES

- OLED menu
- Four-button navigation
- IR file browser
- IR signal sending
- .ir file support
- LittleFS storage
- WiFi scanning
- WiFi connection
- Local WebUI
- Upload IR files through the WebUI
- Basic device information

FILES

The firmware is contained in one Arduino file:

PHANTOM_OS.ino

IR files are stored in:

/ir/

INSTALLATION

1. Install the ESP32 Arduino Core.
2. Install the required libraries.
3. Open PHANTOM_OS.ino in Arduino IDE.
4. Select your ESP32-C3 board.
5. Connect the ESP32-C3.
6. Upload the firmware.

BUTTONS

UP
Move up in menus.

DOWN
Move down in menus.

OK
Select or confirm.

BACK
Go back to the previous screen.

IR FILES

Place .ir files in the /ir/ folder.

You can also upload .ir files through the PHANTOM OS WebUI.

Open the device's local IP address in a browser after connecting it to WiFi.

LIBRARIES

- Adafruit GFX Library
- Adafruit SSD1306
- IRremoteESP8266
- ESP32 Arduino Core

PROJECT INFO

Name: PHANTOM OS
Platform: ESP32-C3 SuperMini
Display: SSD1306 128x64
Storage: LittleFS
IR transmitter: 940nm
Firmware: Arduino
