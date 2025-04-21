🤖 ESP32-Based Web-Controlled Robotic Arm
This project demonstrates a 4-DOF robotic arm controlled wirelessly using an ESP32 microcontroller and a custom web interface. The system allows real-time servo control and features a record-and-playback function for automating movements. Perfect for learning IoT, robotics, and web-based control systems.

🧩 Key Features
Control via web interface (ESP32 creates its own Wi-Fi hotspot)
4 servo motors: Base, Shoulder, Elbow, and Gripper
Real-time position adjustment using sliders
Movement recording and playback
Easy-to-use UI hosted at 192.168.4.1

🛠️ Components Used
1 × ESP32 Development Board
4 × SG90 Servo Motors
Jumper Wires, Breadboard (optional)

⚙️ Servo Pin Configuration
Servo	ESP32 Pin
Base	27
Shoulder	26
Elbow	25
Gripper	33

🌐 How It Works
ESP32 runs an async web server and WebSocket for real-time communication
Users connect to the ESP32 Wi-Fi and open a web page to control the servos
Record and playback functions allow storing and repeating custom sequences

🧪 Getting Started
Upload code to ESP32 using Arduino IDE (select correct board & COM port)
Connect to the Wi-Fi SSID RobotArm (default password: 12345678)
Access the control page at 192.168.4.1
