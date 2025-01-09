# Biometric Library Access System

Welcome to the Biometric Library Access System! This project is designed to provide a secure, low-maintenance access control solution for libraries, ensuring only authorized users can enter.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features
- High-accuracy fingerprint recognition (99% success rate).
- IReal-time user authentication for seamless access.
- OLED display for intuitive status updates.
- Low power consumption for sustainable operation.
- Future potential for additional features like time tracking and integration with library management systems.

## Technologies Used
- ESP32: The core microcontroller for managing operations.
- Fingerprint Scanner Module: For capturing and verifying fingerprints.
- OLED Display: For displaying user feedback and system status.
- Embedded Systems: Ensures efficient interaction between hardware and software.

## Getting Started

### Prerequisites
Ensure you have the following:

- Hardware: ESP32, Fingerprint Scanner Module, OLED Display, jumper wires, and a breadboard or PCB.
- Software: Arduino IDE for uploading the code.

### Installation
1. Clone the repository:
     git clone https://github.com/yourusername/biometric-library-access-system.git  
2. Navigate to the project directory:
      cd biometric-library-access-system
3. Set up the hardware according to the provided circuit diagram.
4. Open the Arduino IDE and install necessary libraries (e.g., Adafruit GFX and Adafruit SSD1306 for the OLED).
5. Upload the code to the ESP32.

### Instructions:
 Hardware Setup
   1. Required Components: ESP32, Fingerprint Scanner, OLED Display, jumper wires, breadboard/PCB.
   2. Connections:
      I) Fingerprint Scanner:
           TX → RX (ESP32), RX → TX, VCC → 3.3V, GND → GND.
     II)  OLED Display:
           SDA → GPIO21, SCL → GPIO22, VCC → 3.3V, GND → GND.

Software Setup: 
  1. Install Arduino IDE from arduino.cc.
  2. Add ESP32 board package:
         Preferences → Additional URLs : https://dl.espressif.com/dl/package_esp32_index.json
         Tools → Board Manager → Install ESP32.
  3. Install libraries:
        Adafruit GFX and Adafruit SSD1306 via Library Manager.
  4. Clone the project:
        git clone https://github.com/yourusername/biometric-library-access-system.git     

## Usage
1. Power on the system.
2. Place your finger on the fingerprint scanner.
3. The OLED display will show:
4. Access Granted: If your fingerprint matches a registered user.
5. Access Denied: If no match is found.
6. Error Message: For any system issues.

## Contributing
Contributions are welcome!
  1. Fork the repository.
  2. Create a new branch for your feature or bug fix:
             git checkout -b feature-name  
  3. Commit and push your changes.
  4. Submit a pull request for review.   

Once you've made the necessary changes, save this as `README.md` in your project directory, and it will automatically be displayed on your GitHub repository's main page.
