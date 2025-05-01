
# 🚚 Smart Delivery Routing System

A Java-based console application that simulates a smart logistics system for managing delivery routes, packages, and dispatching using **Data Structures and Algorithms (DSA)** and **Object-Oriented Programming (OOP)** principles.

---

## 📋 Description

This project models a delivery company’s backend operations, helping optimize delivery paths using Dijkstra’s algorithm, handle urgent packages with PriorityQueue, and simulate dispatch processes. It's designed to demonstrate clean OOP architecture combined with real-world DSA applications.

---

## 🔧 Features

- Add delivery points (nodes) and paths (edges with distance/time)
- Add and prioritize packages (e.g., urgent, standard)
- Calculate optimal delivery routes using **Dijkstra’s algorithm**
- Dispatch deliveries and track history
- Undo last dispatch using a **Stack**
- Visualize or print current route plans and package queues

---

## 🧠 DSA Concepts Used

| Data Structure     | Purpose                                      |
|--------------------|----------------------------------------------|
| `Graph`            | Represent delivery map with routes & distances |
| `PriorityQueue`    | Handle package priority (urgent vs normal)    |
| `HashMap`          | Store delivery point data, package mappings   |
| `Stack`            | Manage delivery history and undo operations   |
| `Dijkstra's Algorithm` | Calculate shortest path between delivery points |

---

## 🧱 OOP Principles Applied

- **Classes**:
  - `Package`: Represents a parcel to be delivered
  - `DeliveryPoint`: Represents a location in the network
  - `RoutePlanner`: Handles shortest path logic using Graph + Dijkstra
  - `DispatchManager`: Controls package dispatch, tracking, and history
  - `DeliverySystem`: Main interface integrating all components

- **Composition**: `DeliverySystem` composes all modules: planner, dispatch, etc.
- **Interfaces**: For strategy patterns (e.g., routing algorithm)
- **SOLID**: Clear separation of concerns, maintainable, and extensible code

---

✅ Future Enhancements
Add file-based saving/loading for persistent data

Implement a GUI using JavaFX

Support traffic conditions using dynamic edge weights

Export delivery logs in CSV format

👨‍💻 Author
Your Name – @SuryanshKumar

