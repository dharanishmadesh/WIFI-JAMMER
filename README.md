

**ESP8266 Deauther (V2.6.1) + OLED (BIN)**

This repository contains the necessary files and instructions to set up an ESP8266 Deauther (V2.6.1) with an OLED display using a pre-compiled binary. 

**Disclaimer:** 
* This project is intended for educational and research purposes only. 
* Using this tool for malicious activities is illegal and unethical. 
* The author of this repository is not responsible for any misuse of this tool.

**Features:**

* **De-authentication attacks:** Disconnects wireless clients from access points.
* **Jamming:** Interrupts wireless communication.
* **Beacon flooding:** Overwhelms the wireless channel with beacon frames. 
* **OLED display:** Displays real-time information such as target MAC address, channel, signal strength, and attack status.

**Hardware:**

* ESP8266 module (NodeMCU, Wemos D1 mini, etc.)
* OLED display (I2C or SPI)
* Micro-USB cable
* Breadboard (optional)
* Jumper wires

**Software:**

* Pre-compiled binary file (included in this repository)
* Arduino IDE (optional, for flashing custom firmware)

**Getting Started:**

1. **Wire the OLED display:**
   * Refer to the OLED display's datasheet for the correct wiring connections.
   * Connect the necessary pins (SDA, SCL, VCC, GND) to the ESP8266.

2. **Flash the binary:**
   * Use a suitable tool (e.g., esptool) to flash the pre-compiled binary file (`deauther_oled.bin`) to the ESP8266.
   * **Note:** Flashing might erase existing firmware on the ESP8266.

3. **Power on the device:** 
   * Connect the ESP8266 to a power source (USB or external power supply).

4. **Control the Deauther:**
   * Refer to the on-screen instructions or the Deauther's documentation for control commands. 
   * You can typically use a serial terminal (e.g., PuTTY, Tera Term) to interact with the Deauther.

**Important Notes:**

* **Safety:** 
    * Be mindful of the legal and ethical implications of using this tool. 
    * Do not use this tool to disrupt legitimate wireless networks without proper authorization.
* **Battery Life:**
    * If using battery power, monitor battery levels to prevent damage to the ESP8266.
* **OLED Brightness:**
    * Adjust the OLED brightness to conserve power and prevent burn-in.

**Disclaimer:**

This README file is for informational purposes only. The author of this repository is not responsible for any issues or damages caused by the use of this tool.

**Contributing:**

Contributions are welcome! Please submit pull requests or create issues on GitHub.

**License:**

This project is licensed under the [Choose a License - e.g., MIT License]. See the LICENSE file for details.

**Remember to:**

* Replace the placeholders with actual values (e.g., specific OLED display model, wiring instructions).
* Add any necessary warnings or disclaimers.
* Include detailed instructions for flashing the binary.
* Provide a list of supported OLED displays (if applicable).
* Consider adding a section on troubleshooting common issues.

I hope this README file is helpful! Let me know if you have any other questions.
