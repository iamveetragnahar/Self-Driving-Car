# Self-Driving Car Project

## Description
This repository contains the code and documentation for a self-driving car prototype. The car uses a combination of hardware and software technologies including C++, OpenCV, Machine Learning, Raspberry Pi, and Arduino Uno to navigate autonomously. By utilizing advanced computer vision techniques and sensor fusion, the car can detect objects, recognize traffic signals, and adhere to traffic rules in real-time.

## Features
- Real-time traffic signal and rules recognition
- Object detection using computer vision techniques
- Obstacle avoidance through sensor fusion
- Model-based engineering and secure system design

## Technical Stack
- Programming Language: C++
- Computer Vision: OpenCV
- Machine Learning for decision making
- Microcontroller: Arduino Uno
- Microprocessor: Raspberry Pi

## Installation & Setup
### Hardware Requirements
- Raspberry Pi (with Raspbian OS installed)
- Arduino Uno
- Cameras and other necessary sensors for object detection and traffic signal recognition
- Motor drivers for actuating the wheels

### Software Setup
Clone the repository:
```sh
git clone 

#Install OpenCV on Raspberry Pi:
sudo apt-get install libopencv-dev
#Install Arduino IDE and upload the provided sketch to the Arduino Uno board.

Running the code
Compile the C++ program on Raspberry Pi:
g++ -o SDC_code SDC_code.cpp `pkg-config --cflags --libs opencv`

Execute the compiled program:
./SDC_code

Usage
Ensure the hardware is set up correctly and the car is placed in a controlled environment. Run the software as instructed above and monitor the car's performance. Adjust the algorithms based on observations and testing.

Contributions
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

To contribute:

Fork the Project
Create your Feature Branch (git checkout -b feature/AmazingFeature)
Commit your Changes (git commit -m 'Add some AmazingFeature')
Push to the Branch (git push origin feature/AmazingFeature)
Open a Pull Request
