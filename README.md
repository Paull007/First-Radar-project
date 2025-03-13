# First-Radar-project
This project uses an Arduino Pro Micro (Leonardo-based) to measure distance with an HC-SR04 ultrasonic sensor. The sensor readings are processed and displayed via the Serial Monitor, and two LEDs blink alternately as the detected distance decreases.
🔹 Features:
  Ultrasonic distance measurement (HC-SR04)
  LED indication based on proximity
  Efficient timing using millis()
  Simple and lightweight code
  
🔧 Hardware Requirements:
  Arduino Pro Micro
  HC-SR04 Ultrasonic Sensor
  2 LEDs + Resistors
  Jumper wires

📜 Usage:
  Upload the provided code to your Arduino Pro Micro.
  Connect the HC-SR04 to appropriate pins (Trig → D5, Echo → D7).
  Observe distance readings in the Serial Monitor and LED behavior based on proximity.
