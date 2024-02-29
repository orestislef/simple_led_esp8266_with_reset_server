# Simple LED ESP8266 with Reset Server

This project enables you to control the onboard LED of an ESP8266 microcontroller using a flush-to-reset server in case of failure to change the MAC address. It consists of two files and can be programmed using the Arduino IDE.

## Files

1. `simple_led_esp8266_with_reset_server.ino`: This is the Arduino sketch file containing the code to control the onboard LED and implement the flush-to-reset server.

2. `README.md`: This file provides information about the project, how to use it, and any additional details.

## Usage

1. **Hardware Setup**: Connect your ESP8266 microcontroller to your development board or USB-to-Serial adapter. Ensure that the necessary drivers are installed for your specific setup.

2. **Arduino IDE Setup**: Open the `simple_led_esp8266_with_reset_server.ino` file in the Arduino IDE.

3. **Select Board and Port**: Choose the appropriate board from the Tools > Board menu and select the correct port from the Tools > Port menu.

4. **Upload Code**: Click the "Upload" button in the Arduino IDE to compile and upload the code to your ESP8266 device.

5. **Control LED**: Once the code is uploaded successfully, the onboard LED of the ESP8266 will be under your control as specified in the sketch.

6. **Reset Server**: In case of failure to change the MAC address, the flush-to-reset server will be triggered to reset the ESP8266 microcontroller.

## Dependencies

- Arduino IDE: Ensure you have the latest version of the Arduino IDE installed on your system.
- ESP8266 Board Support: Install the ESP8266 board support package in the Arduino IDE if you haven't already done so.

## Note

- This project assumes basic familiarity with the Arduino IDE and programming in C++ for microcontrollers.
- Carefully follow the instructions provided in the sketch comments to understand how the code works and make any necessary adjustments for your specific setup.

## Credits

This project is based on the work of contributors to the Arduino community and the ESP8266 core for Arduino.

