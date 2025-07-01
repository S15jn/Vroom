# 🚗 Vroom - Drive Your Way, Instantly

Welcome to **Vroom**, a simple and interactive **Car Rental System** built using **Java Object-Oriented Programming (OOP)** principles. This application allows customers to rent and return cars with ease.

---

## 🛠️ Project Description

**Vroom** is a console-based application for renting and returning cars. It uses classes such as `Car`, `Customer`, `Rental`, and `CarRentalSystem` to demonstrate core OOP concepts including:

- **Encapsulation**
- **Abstraction**
- **Object interaction**
- **Class composition**

---

## 🎯 Tagline

> **Drive Your Way, Instantly**

---

## 📁 Features

- 🏎️ Add and manage available cars.
- 🙋 Customer creation and tracking.
- 📅 Rent cars for a given number of days.
- 💵 Price calculation based on rental duration.
- 🚘 Return rented cars and update availability.
- 📋 Interactive menu-driven system.

---

## 💡 OOP Concepts Used

| Concept            | Implementation                                              |
| ------------------ | ----------------------------------------------------------- |
| **Class & Object** | Classes like `Car`, `Customer`, `Rental`, `CarRentalSystem` |
| **Encapsulation**  | Private fields with public getter/setter methods            |
| **Abstraction**    | Clear separation of car, customer, and rental logic         |
| **Composition**    | `Rental` class composed of `Car` and `Customer`             |

---

## 💻 How to Run

1. **Clone or download** the project.
2. Open it in any Java IDE like IntelliJ IDEA / Eclipse / VS Code.
3. Compile and run `Main.java`.

---

## 📦 Classes Overview

### 1. `Car.java`

- **Attributes:** `carId`, `brand`, `model`, `basePricePerDay`, `isAvailable`
- **Methods:** `rent()`, `returnCar()`, `calculatePrice(days)`

### 2. `Customer.java`

- **Attributes:** `customerId`, `name`

### 3. `Rental.java`

- **Attributes:** `Car`, `Customer`, `days`

### 4. `CarRentalSystem.java`

- **Responsibilities:** Manage cars, customers, rentals, and user interface

### 5. `Main.java`

- **Purpose:** Entry point — initializes the system and runs the menu

---

## 📷 Sample Output

```text
===== Vroom-Drive Your Way, Instanly =====
===== Car Rental System =====
1. Rent a Car
2. Return a Car
3. Exit
Enter your choice:
```

---

## 🔄 Future Enhancements

- Add admin functionality to manage cars
- Store rental records in a file or database
- Implement GUI using JavaFX or Swing
- Include payment gateway simulation

---

## 🧑‍💻 Author

**Somya Jain**  
_Final Year MCA Student_  
Project inspired by real-world rental systems with simplified logic.

---

## 📄 License

This project is open-source and free to use for learning purposes.
