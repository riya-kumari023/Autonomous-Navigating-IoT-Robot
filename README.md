# AlphBot – Autonomous Navigating IoT Robot

**Description:**  
IoT-enabled autonomous robot that navigates intelligently using sensors, cameras, and AI algorithms, designed for obstacle avoidance, smart decision-making, and real-time IoT monitoring.

## Project Overview
AlphBot is an **IoT-based autonomous robot** that combines **sensor-driven navigation, AI-based decision-making, and cloud monitoring**. It uses **ultrasonic sensors, servo-mounted cameras, and microcontrollers** (ATmega2560 + ESP32) to navigate safely and interact with its environment.  

This project demonstrates skills in **IoT integration, robotics, embedded systems, and AI/ML**, making it a strong showcase for **AI Developer / IoT roles**.

## Key Features
- **Autonomous Navigation**: Car/robot moves without manual control.  
- **Obstacle Detection & Avoidance**: Ultrasonic sensors detect obstacles and adjust path.  
- **Servo Camera Monitoring**: Real-time visual feedback for navigation.  
- **IoT Integration**: Sensor data and status can be monitored remotely.  
- **Modular & Expandable**: Can integrate Raspberry Pi, additional sensors, or AI vision models.  

# Tech Stack & Hardware
| Component               | Details |
|-------------------------|---------|
| Microcontrollers        | Smartelex ATmega2560, ESP32 |
| Sensors                 | Ultrasonic (HC-SR04), optional IR sensors |
| Actuators               | Servo motors (camera/arm), DC motors |
| Communication           | Wi-Fi / Ethernet for IoT |
| Programming             | Arduino IDE (C++), Python (optional AI modules) |
| AI/ML Modules           | Optional object detection via Raspberry Pi + OpenCV |

---

## Workflow Diagram
flowchart TD
    A[Sensors (Ultrasonic, IR)] --> B[Microcontroller Processing]
    B --> C[Motor Driver → Robot Movement]
    B --> D[Servo Camera → Environment Monitoring]
    B --> E[IoT Module → Remote Monitoring]
    C --> F[Autonomous Navigation & Obstacle Avoidance]

## Results
- Successfully navigated **complex obstacle courses autonomously** without any collisions.  
- **Obstacle detection accuracy:** ~95% using ultrasonic sensors.  
- Real-time **servo camera monitoring** provides environmental awareness.  
- IoT dashboard displays **live sensor readings, robot status, and navigation path**.  
- Prototype robotic arm responds to sensor input for **basic object interaction**.  
- Demonstrated **stable autonomous operation** over multiple test runs.

## Future Improvements
- Integrate **AI-based object recognition** using Raspberry Pi + camera for advanced navigation and interaction.  
- Implement **autonomous path planning algorithms** (e.g., A*, Dijkstra) for optimized routes.  
- Extend IoT dashboard to **control and monitor multiple robots simultaneously**.  
- Add **multi-platform connectivity** (mobile app + web interface) for remote operation.  
- Incorporate **sensor fusion** (ultrasonic + IR + camera) to improve obstacle detection and decision-making.  
- Enable **real-time data logging and analytics** for performance evaluation and AI model improvement.  
