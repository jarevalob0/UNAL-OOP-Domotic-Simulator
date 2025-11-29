# Workshop 4 — Layered Architecture Implementation
### Object-Oriented Programming — Universidad Nacional de Colombia

This folder contains all the deliverables for **Workshop 4**, which focuses on applying a **layered software architecture** to the Domotic Circuit Simulator developed in previous assignments.  
The goal of this workshop is to reorganize the system using the Presentation, Business Logic, and Data layers while ensuring clean separation of responsibilities and maintainability.

---

## 📄 Contents

### 1. Workshop_4.pdf  
The main document including:
- Layered design review  
- UML layered model  
- Layered code organization  
- Initial implementation snippets  
- Submission format description  

### 2. UML Diagram  
A visual UML representation of the three-layer architecture:
- Presentation Layer  
- Business Logic Layer  
- Data Layer  

The diagram illustrates class grouping, inheritance, dependencies, and architectural boundaries.

File included:  
- `UML_Layered_Architecture.png`

---

## 🧩 Summary of the Architecture

The simulator is now organized into three separate layers:

### **Presentation Layer**
Handles all user interaction through a PyQt5-based interface. It forwards actions to the underlying logic without implementing behavior itself.

### **Business Logic Layer**
Contains the core simulation: components, circuit management, and simulator execution. This layer defines how the domotic system behaves.

### **Data Layer**
Responsible for saving/loading circuits through JSON serialization. It interacts with the Business Layer but never with the Presentation Layer.

---

## 🗂️ Directory Structure


