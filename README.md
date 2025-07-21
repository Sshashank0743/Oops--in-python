Here are some Object-Oriented Programming (OOP) related practice questions in Python. These will help you understand key concepts such as classes, objects, inheritance, polymorphism, encapsulation, and abstraction.

1. Class and Object Basics
Create a class Book with the following attributes: title, author, year_published. Write a method book_info() that returns a string with the book’s details.

Create an object of the class Book and display the details using the book_info() method.

2. Encapsulation
Create a class Car with the following attributes: make, model, and year. The year should not be directly accessible. Provide a method get_year() to access the year.

Create a setter method set_year() to update the year. If the year is not a valid year (should be an integer greater than 1885), raise an error.

3. Inheritance
Create a base class Animal with methods like speak() and eat().

Create two derived classes Dog and Cat that inherit from Animal. Implement the speak() method differently for each of the derived classes (e.g., "Woof!" for Dog, "Meow!" for Cat).

Instantiate objects of Dog and Cat and call their methods.

4. Polymorphism
Create a class Shape with an abstract method area(). Create two derived classes Rectangle and Circle that implement the area() method.

Instantiate both shapes and display their area.

5. Abstraction
Define an abstract class Vehicle with an abstract method drive(). Create two classes, Car and Bike, that implement the drive() method.

Instantiate objects of Car and Bike and call their drive() method.

6. Class Method and Static Method
Create a class Student with the attributes name, age, and marks. Write a class method average_marks() that calculates and returns the average marks of all students.

Create a static method is_eligible_for_promotion() to check if a student is eligible for promotion (marks >= 50).

7. Operator Overloading
Define a class Vector that represents a vector in a 2D plane. Implement the + operator to add two vectors (i.e., v1 + v2 should add corresponding components of the vectors).

Implement the __str__ method to return a string representation of the vector.

8. Method Resolution Order (MRO)
Create a class A, a class B that inherits from A, and a class C that also inherits from A. Create a class D that inherits from both B and C.

Investigate the method resolution order of the class D by printing D.__mro__.

9. Custom Exceptions
Define a custom exception class InvalidAgeException that will be raised if a user tries to set the age of a person below 0 or above 120.

Create a class Person with an age attribute. Set the age using a setter method, and raise the InvalidAgeException if the age is not valid.

10. Class vs Instance Attributes
Create a class BankAccount with an instance attribute balance and a class attribute interest_rate. Create methods to deposit, withdraw, and check balance.

Use the class attribute interest_rate to calculate the interest earned on the balance.
