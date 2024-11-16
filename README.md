# BrainControlCar

In this project, I developed a brain-controlled car using an EEG (Electroencephalography) sensor, an ESP32 microcontroller, and RF (Radio Frequency) sensors. The goal was to enable a car to be controlled directly through brain signals, providing a hands-free, intuitive interface for controlling the vehicle.

Key Components:
EEG Sensor: The EEG sensor captures brainwave activity and processes it to detect specific mental states or intentions. This data is used to trigger certain commands (e.g., moving forward, turning, stopping).

ESP32: The ESP32 microcontroller serves as the brain of the system. It communicates with the EEG sensor to receive brainwave data and then processes this information to generate control signals for the car. The ESP32 also handles communication with the RF module for transmitting control commands to the car.

RF Sensors/Module: RF sensors are used to wirelessly transmit the processed signals from the ESP32 to the car's control system. This allows the user to control the car's movements remotely via brainwave signals, without needing physical buttons or joysticks.

Functionality:

Brainwave Signal Processing: The EEG sensor captures brainwave signals, which are analyzed for patterns. 

Car Control: The ESP32, based on the brainwave input, sends appropriate commands to the car’s motor control system via the RF sensors. 

Wireless Communication: The RF sensors enable seamless communication between the ESP32 and the car, allowing for real-time control without direct physical interaction.

Application and Future Improvements:
This project demonstrates the potential for brain-computer interfaces (BCIs) in controlling everyday devices. Although the current implementation is for a toy car, the technology could be scaled for real-world applications like assisting people with disabilities or enhancing robotics systems. Future improvements could include better signal processing algorithms, more precise control, and enhanced reliability in detecting brainwave patterns.

This project combines neuroscience, embedded systems, and wireless communication to create an innovative solution for controlling a car with only brain signals.






https://github.com/user-attachments/assets/7c7139af-c608-426b-8806-31835a83a0c8

