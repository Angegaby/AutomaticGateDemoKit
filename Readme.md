# AutomaticGateDemoKit

This project simulates an automatic gate using an Arduino Uno and common components. The system responds to approaching objects and opens/closes the gate accordingly.

## Features

- **Ultrasonic Sensor**: Detects objects within a 50 cm range.
- **Servo Motor**: Opens (90°) and closes (0°) the gate.
- **LED Indicators**:
  - Red LED = Gate Closed
  - Blue LED = Gate Open
- **Buzzer**: Beeps continuously (non-blocking) while the gate is open.

## Components

- Arduino Uno
- HC-SR04 Ultrasonic Sensor
- SG90 Servo Motor
- Red LED
- Blue LED
- Piezo Buzzer
- Resistors, wires, breadboard

## File

- `automatic_gate.ino` — Main Arduino sketch controlling gate behavior.

## Behavior

- If an object is detected within the threshold distance (50 cm), the gate opens.
- The gate stays open while the object is present.
- Once the object is gone, the gate waits 5 seconds before closing.
- Visual and audio indicators reflect the current gate state.

---

🛠 Ready for testing on the Automatic Gate Demo Kit!
