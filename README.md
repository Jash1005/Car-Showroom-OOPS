#  Car Company Management System 

Welcome to the **Car Company Management System**, a simple Java-based console application designed to showcase Object-Oriented Programming (OOP) concepts in action.

This project allows a car company to:
- Register multiple **showrooms** with basic details  
- Add **employees** with department and age information  
- Add **cars** with specifications like fuel type, transmission, and price  

All employee and car entries are stored **at the company level**, not showroom-specific, but you can still note the showroom name as a field for reference.

---

##  Tech Stack

- **Language**: Java
- **Core Concepts**: OOP (Classes, Inheritance, Interfaces), Arrays, Console I/O

---

##  How It Works

- The program starts with a **main menu** offering options to:
  1. Add Showroom  
  2. Add Employee  
  3. Add Car  
  4. View All Showrooms  
  5. View All Employees  
  6. View All Cars  

- Each option prompts the user to enter relevant details via the terminal.
- All data is stored in arrays with a maximum of 10 records for each type (can be extended).
- UUIDs are used to auto-generate unique employee IDs.
- Every class implements a `utility` interface with methods to set and display details.

---

##  Sample Flow

```text
======================= *** WELCOME TO SHOWROOM MANAGEMENT SYSTEM *** =======================
1].ADD SHOWROOMS        2].ADD EMPLOYEES        3].ADD CARS
4].GET SHOWROOMS        5].GET EMPLOYEES        6].GET CARS
ENTER YOUR CHOICE: 1
```

##  Project Structure

| Class/File | Purpose |
|------------|---------|
| `Main.java` | Entry point of the program with a menu-driven interface |
| `showroom.java` | Represents a showroom with name, address, and manager |
| `Employees.java` | Extends `showroom`, holds employee details like name, age, department |
| `Cars.java` | Extends `showroom`, holds car details like name, fuel type, price |
| `utility` interface | Defines `set_details()` and `get_details()` methods implemented by all classes |

---
 # Concepts Used
 1. Interface
 2. Overriding
 3. Polymorphism
