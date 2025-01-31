# 🚗 Smart Remote Car with Automatic QR Code Navigation

Welcome to the **Smart Remote Car** project! This repository contains the code and documentation for a remote-controlled car equipped with an **automatic driving mode** that scans and processes **QR codes** along its journey.  

## 🎯 Project Overview

This project aims to develop a **remote-controlled car** that can:  
- Be manually controlled via a remote interface  
- Switch to an **autonomous mode**, navigating based on QR codes  
- Detect, read, and interpret QR codes to make driving decisions  
- Log and process QR data for further analysis  

## 🏗️ System Architecture

The project consists of multiple components:  

- **Hardware**:  
  - Microcontroller (e.g., Raspberry Pi in our case)  
  - Camera module for QR code detection  
  - Motor drivers and wheels ofc :-)
  - a thin wooden board cut to fit the Raspberry Pi
  - Wireless module for remote control
  - aruco markers, mounts (https://www.chev.me/arucogen)

- **Software**:  
  - QR code recognition using OpenCV  
  - Path planning and decision-making logic  
  - Web or mobile interface for manual control (HTML/CSS/Javascript)

## 📂 Repository Structure  

**Link to the repository :** https://github.com/AbdennourKerPro/Smart-Remote-Car-with-Automatic-QR-Code-Navigation

```plaintext
📦 Smart-Remote-Car
 ├── 📁 Parcours Automatique          # Code running on the car’s microcontroller
 ├── 📁 Interface      # Remote control dashboard
 ├── README.md             # You are here!
