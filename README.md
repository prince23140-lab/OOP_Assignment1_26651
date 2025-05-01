# Assignment One – OOP Java Projects with Docker

This repository contains solutions for three Object-Oriented Programming (OOP) assignments implemented in Java and containerized using Docker:

1. 🚀 Mission Management System  
2. 🌍 Land Management System  
3. 🌱 Nursery Management System  

Each project uses clean OOP principles, strong validation, and follows modular design for maintainability.

---

## 🚀 1. Mission Management System

### 🔹 Description
The **Mission Management System** simulates managing different types of missions (e.g., scientific, military, commercial). It features polymorphic mission classes, mission cost calculations, and validations.

### 🔧 Technologies Used
- Java (OOP Concepts)
- Docker
- CLI-based interaction

### 🛠️ How to Build
```bash
javac missionManagementSystem/*.java

```
### ▶️ How to Run (Locally)
```bash

java missionManagementSystem.Main

```
### 🐳 Docker Usage
Build Docker Image

```bash
docker build -t oop_26651_missionmanagementsystem .

```
#### Tag for Docker Hub
```bash

docker tag oop_26651_missionmanagementsystem lion23140/assignment_one_26651:missionmanagementsystem
```
#### Push to Docker Hub
```bash

docker push lion23140/assignment_one_26651:missionmanagementsystem

```
#### Run Container
```bash

docker run -it lion23140/assignment_one_26651:missionmanagementsystem

```
### 🌍 2. Land Management System
#### 🔹 Description
The Land Management System manages various land types (residential, commercial, agricultural), calculates taxes or usage fees, and ensures validation based on land area or type.

### 🔧 Technologies Used
- Java (Inheritance, Abstraction)
- Docker

### 🛠️ How to Build
```bash

javac landManagementSystem/*.java
```
### ▶️ How to Run (Locally)
```bash

java landManagementSystem.Main
```
###  🐳 Docker Usage

Build Docker Image
```bash

docker build -t oop_26651_landmanagementsystem .
```
#### Tag & Push
```bash

docker tag oop_26651_landmanagementsystem lion23140/assignment_one_26651:land_management_system
docker push lion23140/assignment_one_26651:land_management_system
```
#### Run
```bash

docker run -it lion23140/assignment_one_26651:land_management_system

```
### 🌱 3. Nursery Management System
#### 🔹 Description
The Nursery Management System helps track different types of plants, their water needs, growth stages, and pricing for sale or transplanting. Demonstrates polymorphism, abstraction, and encapsulation.

### 🔧 Technologies Used
- Java (OOP Best Practices)

- Docker

### 🛠️ How to Build
```bash

javac nurseryManagementSystem/*.java

```
### ▶️ How to Run (Locally)
```bash

java nurseryManagementSystem.Main
```
### 🐳 Docker Usage

#### Build Docker Image
```bash

docker build -t oop_26651_nurserymanagementsystem .
```
Tag & Push
```bash

docker tag oop_26651_nurserymanagementsystem lion23140/assignment_one_26651:nursery_management_system
docker push lion23140/assignment_one_26651:nursery_management_system
```
Run
```bash

docker run -it lion23140/assignment_one_26651:nursery_management_system
```

## 👤 Author
### Nziza Prince – 26651
- OOP Project | Assignment One
- Docker Hub: lion23140


