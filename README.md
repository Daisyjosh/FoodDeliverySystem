# 🍔 Food Delivery System (OOP-Based)

## 📖 Description
A console-based food delivery system built using Python and Object-Oriented Programming principles.  
The application simulates a real-world food ordering platform with cart management, order processing, and review systems.

---

## 🚀 Features
- 🧾 Browse Menu from Multiple Restaurants  
- 🛒 Add Multiple Items to Cart  
- 📦 Place Orders with Status Tracking  
- 🧑‍🍳 Restaurant & Delivery Person Reviews  
- 📊 View Order History  
- 💬 Customer Review System  

---

## 🏗️ Architecture
This project follows a layered architecture:

- **View Layer** → Handles user interaction (CLI)  
- **Controller Layer** → Manages request flow  
- **Service Layer** → Business logic  
- **Repository Layer** → Data storage (in-memory)  
- **Models** → Core entities (Customer, Order, Menu, etc.)  

---

## 🧠 OOP Concepts Used
- **Encapsulation** → Data handling inside models  
- **Abstraction** → Service layer hides business logic  
- **Inheritance** → User → Customer / DeliveryPerson  
- **Separation of Concerns** → Each layer has a clear role  

---

## 🔄 System Flow
1. Customer views food menu  
2. Adds items to cart  
3. Reviews cart and confirms order  
4. Order is created and assigned  
5. Customer can:
   - View order history  
   - Leave reviews  
6. System maintains order and review records  

---

## ⚙️ Tech Stack
- Python 3  
- Object-Oriented Programming (OOP)  

---
```text
## 📂 Project Structure
project-root/
│
├── controller/
├── service/
├── repository/
├── model/
├── view/
│
├── main.py
├── README.md
└── .gitignore
```

---

## 🧠 Key Learnings
- Designing multi-layer architecture  
- Managing complex control flow  
- Implementing cart and order lifecycle  
- Handling user interactions in CLI systems  

---

## 🔮 Future Improvements
- Add authentication system  
- Convert to web app (React + Node.js)  
- Add database integration (MongoDB / SQL)  
- Implement real-time order tracking  

---

## 🙌 Author
**Daisy Panimaryial**

---

## ⭐ Note
This project was built completely from scratch without using AI, focusing on understanding system design and flow control.
