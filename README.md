# Fileflow 📂⏳ - Communication Desing Project Semester 3 
![file share](https://github.com/maduwanthasl/Fileflow-Communication-Desing-Project-Semester-3/blob/main/Pictures/R.png)
## Introduction

The **Fileflow** project, part of our Semester 3 Communication Design module, aims to create a simple, robust file sharing system for audio, video, and text files between two computers. This system employs RTL-SDR (Software Defined Radio) and BladeRF devices, known for their flexibility and high performance in wireless communication. Utilizing GNU Radio software, we will implement the software components necessary for encoding, transmitting, receiving, and decoding files, ensuring a customizable and efficient communication pipeline. This project highlights the practical applications of these advanced technologies in modern file sharing solutions.

## Requirements

The Fileflow project entails the development of a point-to-point digital wireless communication system using software-defined radios (SDRs). The following are the key requirements for the project:

#### Communication System Implementation:
- Design and implement a digital wireless communication system that uses RTL-SDR and BladeRF devices to establish a secure and reliable connection between two computers.
#### Security and Reliability:
- Ensure that communications are both secure and reliable, incorporating measures to prevent eavesdropping and mitigate the effects of external jamming.
#### Transmitter Design:
- Encoding: Develop encoding mechanisms to prepare files for transmission.
- Security Implementation: Implement security protocols to protect data.
- Reliability Enhancement: Include features to enhance the reliability of data transmission.
- Jamming Protection: Integrate protection against potential jamming attacks.
- Modulation: Apply suitable modulation techniques for effective data transmission.
#### Receiver Design:
- Reliability Enhancement: Implement measures to enhance the reliability of received data.
- Demodulation: Develop demodulation techniques to accurately retrieve data from the signal.
- Decoding: Create decoding methods to reconstruct the original files from the received data.

#### Operational Parameters:
- Frequency Band: Operate the system within the 2.4 GHz ISM band, adhering to maximum power limitations to comply with regulations.
- User Interface: Design a user-friendly interface to facilitate easy operation and monitoring of the system.

#### Performance Evaluation:
- Assess the system's performance by evaluating communication effectiveness over varying distances and measuring end-to-end delay to ensure minimal latency.

#### Optional Features:

- Channel Estimation: Implement techniques to estimate channel conditions for optimizing communication parameters.
- Adaptive Transmission: Incorporate adaptive transmission methods to adjust to changing channel conditions dynamically.
- Closed-Loop System: Develop a closed-loop system to enhance communication efficiency and reliability through feedback mechanisms.

## The Main Block diagram of the communication system

![Block diagrma](https://raw.githubusercontent.com/maduwanthasl/Fileflow-Communication-Desing-Project-Semester-3/main/Pictures/block%20diagram.png)
