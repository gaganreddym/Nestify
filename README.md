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

## 📁 Project Structure

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

## ▶️ Getting Started

### Prerequisites
- Java 8+

### Run the Project
```bash
javac Main.java
java Main

---

