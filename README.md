# 🚇 Patna Metro Route Finder

![Java](https://img.shields.io/badge/Java-17%2B-blue.svg)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.5.3-brightgreen.svg)
![MongoDB](https://img.shields.io/badge/MongoDB-%2324292e.svg?logo=mongodb&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green.svg)

---

## 📌 **Project Overview**

Patna Metro Route Finder is a **Java Spring Boot** based backend application to:

- Store all metro stations of Patna Metro (Red Line & Blue Line)
- Find routes between two stations
- Manage station data in MongoDB
- Provide REST APIs for route finding and station listing

---

## 💡 **Features**

✅ REST APIs for CRUD operations on Stations  
✅ Route finding between two stations (line-wise basic implementation)  
✅ MongoDB integration for data persistence  
✅ CommandLineRunner seeder for initial station data  
✅ Extensible architecture for future enhancements (graph-based routes, fares, timings, UI integration)

---

## 🚀 **Tech Stack**

- **Backend:** Java 24, Spring Boot 3.5.3
- **Database:** MongoDB Atlas or Local MongoDB
- **Build Tool:** Maven

---

## 🛠️ **Project Structure**
```
patna-metro/
├── src/
│ ├── main/
│ │ ├── java/com/bihar/patna_metro/
│ │ │ ├── controller/
│ │ │ ├── model/
│ │ │ ├── repository/
│ │ │ ├── service/
│ │ │ └── PatnaMetroApplication.java
│ │ └── resources/
│ │ └── application.properties
└── pom.xml
```
