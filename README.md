Car Rental System

Overview:
The Car Rental System is a Java-based application that allows customers to rent and return cars seamlessly. It manages a fleet of cars, keeps track of rental transactions, and provides an intuitive menu-driven interface for customers and administrators.

Features:
Add Cars to the System: Administrators can define a fleet of cars available for rental.
Rent a Car: Customers can select a car, specify the rental duration, and calculate the total rental cost.
Return a Car: Customers can return rented cars and update the system's availability.
User-Friendly Interface: A menu-driven interface for easy navigation.
Rental Records: Tracks customer and rental information.

Classes and Functionality:

1. Car:   
Represents a car with attributes such as:
Car ID
Brand
Model
Base rental price per day
Availability status

2. Customer:
Represents a customer with attributes:
Customer ID
Name

3. Rental:
Tracks rental details including:
Associated car
Customer who rented it
Number of rental days

5. CarRentalSystem:
Manages:
A list of available cars
Customer records
Rental transactions
Menu-driven operations for renting and returning cars

5. Main:
The entry point for the application.
Requirements
Java Development Kit (JDK) version 8 or higher.
A text editor or IDE (e.g., IntelliJ IDEA, Eclipse, or VS Code).

Menu Options:
Rent a Car:
Enter your name.
View a list of available cars.
Select a car by its ID.
Enter the rental duration to view the total cost.
Confirm the rental to complete the transaction

Return a Car:
Provide the ID of the car to be returned.
The system updates the car's availability.

Exit:
Exits the application.
