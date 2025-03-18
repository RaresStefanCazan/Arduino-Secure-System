# Arduino Secure Encryption/Decryption System

This project is a secure system implemented on an Arduino platform that provides a password-protected interface with encryption and decryption capabilities. The system features a menu-driven user interface displayed on an I2C LCD and supports multiple encryption algorithms such as Caesar, XOR, and Vigenere ciphers. Additionally, it includes functionalities for changing settings, generating random passwords, and more.

---

## Features

- **Password-Protected Access:**
  - Users must log in by entering a password (stored in EEPROM).
  - The system locks out and triggers an alarm after three failed login attempts.

- **Menu-Driven Interface:**
  - Main menu options include encryption, decryption, settings, change password, algorithm selection, Vigenere key update, and random password generation.
  - Navigation is achieved via push buttons for menu selection and confirmation.

- **Encryption/Decryption Algorithms:**
  - **Caesar Cipher:** Shifts characters by a configurable key.
  - **XOR Cipher:** Applies an XOR operation for basic encryption/decryption.
  - **Vigenere Cipher:** Uses a keyword to perform encryption/decryption.

- **Real-Time Interaction:**
  - The system displays messages and results immediately on the LCD.
  - Provides instant visual (LED indicators) and audio (buzzer alerts) feedback.

- **EEPROM Storage:**
  - The user password is stored persistently in EEPROM for subsequent sessions.

- **Additional Functionalities:**
  - Random password generation with a configurable length.
  - Ability to change the Vigenere key and select the desired encryption algorithm.

---

## Hardware Requirements

- **Arduino Uno** (or a compatible board)
- **I2C LCD Display** (16x2)
- **Push Buttons:** For menu navigation and selection
- **LEDs:** Green (for success) and Red (for error/alert indication)
- **Buzzer:** For audio alerts
- **Resistors and Wiring:** As specified in the provided schematic (Wokwi simulation available)

---

## Simulation Diagram

For those who wish to run this project on a simulator (such as Wokwi), a `diagram.json` file is provided in this repository. Simply import the `diagram.json` into your simulator to set up the project environment and test it virtually.


---


