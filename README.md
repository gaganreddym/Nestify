# 🏠 Nestify - Smart Home Simulator

## 🚀 Overview
Nestify is a smart home simulation system built in Java using Object-Oriented Programming (OOP) and SOLID design principles.  
It models interactions between IoT devices such as smart lights and thermostats through a centralized controller.

The focus of this project is on scalability, maintainability, and extensibility using clean architecture and design patterns.

---

## 🎯 Features
- Simulated IoT devices (Smart Lights, Thermostats)
- Centralized controller for managing devices
- Real-time state synchronization
- Extensible design for adding new devices
- Modular and maintainable architecture

---

## 🏗️ System Design

### Core Components

#### 1. Device Interface
- Defines common behaviors for all devices  
- Example methods: `turnOn()`, `turnOff()`

#### 2. Concrete Devices
- SmartLight  
- Thermostat  
Each device implements core functionality

#### 3. Controller
- Manages all connected devices  
- Sends commands and coordinates state updates  

---

## 🧠 Design Patterns Used

### Observer Pattern
- Enables real-time updates between controller and devices  

### Factory Pattern
- Handles dynamic object creation  

### Singleton Pattern
- Ensures a single instance of the controller  

---

## ⚙️ Tech Stack
- Java  
- Object-Oriented Programming (OOP)  
- SOLID Principles  
- Design Patterns (Observer, Factory, Singleton)  

---


## 📂 Project Structure
```
Nestify/
├── devices/
│ ├── SmartLight.java
│ ├── Thermostat.java
├── controller/
│ ├── HomeController.java
├── factory/
│ ├── DeviceFactory.java
├── interfaces/
│ ├── Switchable.java
│ ├── Dimmable.java
├── main/
│ ├── Main.java
```

---
## 📈 Future Improvements
- Add support for more device types  
- Introduce event-driven architecture  
- Add persistence for device states  
- Build REST APIs for remote control  

---

## 💡 Key Learnings
- Applying SOLID principles in real systems  
- Designing scalable architectures  
- Using design patterns effectively  
- Writing maintainable Java code  

---

## 🤝 Contributing
Contributions are welcome. Fork the repository and submit a pull request.

