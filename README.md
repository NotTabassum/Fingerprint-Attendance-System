# Fingerprint Attendance System

This project is a Fingerprint Attendance System built using an Arduino Uno. It registers attendance using a fingerprint sensor and includes both hardware and software components.

## Hardware Components
- **Arduino Uno**
- **R305S Fingerprint Sensor**
- **DS1307 RTC Module**
- **16x2 LCD Display**
- **4 Push Buttons (Switches)**
- **Breadboard**
- **Wires/Cables**

### Push Button Functions:
1. **Register/Back Button** - Enroll a new fingerprint or return to the menu.
2. **Delete/OK Button** - Delete stored fingerprints or confirm actions.
3. **Up Button** - Navigate upwards when selecting memory locations.
4. **Down Button** - Navigate downwards when selecting memory locations.

### System Operations:

#### Enroll a New Fingerprint:
1. Press the **Register/Back** button.
2. Use the **Up/Down** buttons to select the roll number for storing the fingerprint.
3. Press **OK**.
4. Follow the instructions on the LCD (place and remove your finger twice).
5. The fingerprint is successfully stored.

#### Delete a Fingerprint:
1. Press the **Delete/OK** button.
2. Use the **Up/Down** buttons to select the roll number with the fingerprint to delete.
3. Press **OK** to confirm.
4. The fingerprint is successfully deleted.

#### Retrieve Attendance:
1. To get the attendance for the day, press the **Register/Back** button and the reset button together.
2. Open the **Serial Monitor** to view and collect the attendance log.

## Software
The code is written using **Arduino IDE**. It handles the interactions with the fingerprint sensor, real-time clock module, LCD display, and push buttons.

## Setup and Usage
1. Connect the hardware components as shown in the circuit diagram provided in the repository.
2. Upload the Arduino code from the `src` folder using the Arduino IDE.
3. Follow the instructions on the LCD and the buttons to enroll, delete fingerprints, and retrieve attendance.
