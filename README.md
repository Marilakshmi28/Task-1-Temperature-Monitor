COMPANY:CODTECH IT SOLUTIONS
NAME:MARILAKSHMI S
INTERN ID:CT04DH848DOMAIN:EMBEDDED SYSTEMS
DURATION:4 WEEKS
# Task-1-Temperature-Monitor
Internship project-Temperature sensor using TMP36
Task 1 – Temperature Monitoring System using TMP36

This project reads temperature using the TMP36 sensor and displays it on the Arduino Serial Monitor. The circuit is simulated using Tinkercad.

Components Used:
- Arduino UNO
- TMP36 Temperature Sensor
- Jumper Wires

Circuit Description:
- TMP36 VCC (left pin) → 5V on Arduino  
- TMP36 VOUT (middle pin) → A0 on Arduino  
- TMP36 GND (right pin) → GND on Arduino

Formula Used
Voltage = analogRead(A0) * (5.0 / 1023.0);
Temperature = Voltage * 100;

