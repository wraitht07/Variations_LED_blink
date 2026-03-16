📌 Project Overview
This project explores the fundamentals of Embedded Systems and Control Logic. Before diving into complex AI and Mobile Robotics, I’m mastering how to talk to hardware through electricity and C++.

💡 Variations of the "Blink"
I’ve progressed through three main stages of LED control. Each stage represents a core concept used in real-world robotics:

1. The Classic Digital Blink 🚥
The Logic: Basic binary state control (HIGH vs LOW).

What I learned: Polarity (Anode vs Cathode), current limiting with resistors, and the digitalWrite() function.

Real-world use: Turning a robot's power on/off or signaling a simple "System Ready" status.

2. Sequential "Traffic Light" Logic 🚦
The Logic: Time-based state machines using delay().

What I learned: Controlling multiple pins (9, 10, 11) in a specific order.

Real-world use: Executing a sequence of movements (e.g., Robot: Lift Arm -> Open Claw -> Drop Item).

3. PWM "Breathing" & Cross-Fading ✨
The Logic: Using Pulse Width Modulation via analogWrite().

What I learned: Gradual power transition. Instead of a "snap" on/off, I implemented a smooth fade-in and fade-out. I even pushed it further by cross-fading two LEDs simultaneously by tuning the delay and duty cycles.

Real-world use: Smooth motor acceleration/deceleration to prevent robot tipping and "breathing" UI lights for user-friendly bots.

🛠️ Tech Stack
Simulator: Tinkercad 💻

Microcontroller: Arduino Uno R3 🧠

Language: C++ (Arduino Sketch) 📝

Key Concepts: PWM, Serial Communication
