# 🐍 Python OOP Practice Questions

This repository contains beginner-to-intermediate level **Object-Oriented Programming (OOP)** practice questions in **Python**. The questions cover essential OOP principles such as:

- Classes & Objects
- Encapsulation
- Inheritance
- Polymorphism
- Abstraction
- Class vs Instance attributes
- Operator Overloading
- Method Resolution Order (MRO)
- Custom Exceptions

---

## 🔧 Requirements
- Python 3.6+
- No external libraries required

---

## 📚 Practice Questions & Topics

### 1. 📘 Class and Object Basics
Create a class `Book` with attributes `title`, `author`, and `year_published`. Include a method `book_info()` that returns the book details.

🔹 **Task:** Instantiate a `Book` object and display its details.

---

### 2. 🔐 Encapsulation
Create a class `Car` with attributes `make`, `model`, and a **private** attribute `year`. Use getter and setter methods for controlled access. The `year` must be an integer greater than 1885.

---

### 3. 🐾 Inheritance
Create a base class `Animal` with methods like `speak()` and `eat()`. Derive classes `Dog` and `Cat`, each with its own implementation of `speak()`.

🔹 **Task:** Demonstrate polymorphic behavior via method overriding.

---

### 4. 🔄 Polymorphism
Create an abstract class `Shape` with an abstract method `area()`. Implement derived classes `Rectangle` and `Circle`.

🔹 **Task:** Calculate and print the area of both shapes using polymorphism.

---

### 5. 🏍️ Abstraction
Create an abstract class `Vehicle` with an abstract method `drive()`. Implement classes `Car` and `Bike` that define the `drive()` method.

---

### 6. 🎓 Class Method and Static Method
Create a class `Student` with attributes `name`, `age`, and `marks`. Add:
- A **class method** `average_marks()` to compute average marks of all students.
- A **static method** `is_eligible_for_promotion()` that returns `True` if `marks >= 50`.

---

### 7. ➕ Operator Overloading
Define a class `Vector` to represent a 2D vector. Implement the `+` operator to add two vectors, and `__str__()` for printable representation.

---

### 8. 🔄 Method Resolution Order (MRO)
Create classes `A`, `B(A)`, `C(A)`, and `D(B, C)`. Print `D.__mro__` to analyze method resolution order in multiple inheritance.

---

### 9. ❗ Custom Exceptions
Create a custom exception `InvalidAgeException`. Create a class `Person` that uses a setter to assign age and raises the exception if age is not between 0–120.

---

### 10. 🏦 Class vs Instance Attributes
Create a class `BankAccount` with:
- An **instance attribute**: `balance`
- A **class attribute**: `interest_rate`

Add methods for:
- `deposit()`
- `withdraw()`
- `calculate_interest()`

---

## 📁 Directory Structure (Suggestion)
