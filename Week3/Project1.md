# Project 1: Food Delivery App
The Food Delivery App is a console-based application that allows users to order food that they want delivered to them. Admins can add food items.

## Technical Requirements
1. Functionality should reflect the below user stories.
2. Data is stored in an Oracle database.
3. Data access is performed through Hibernate in a data layer consisting of Data Access Objects.
4. All input is received using the java.util.Scanner class.
5. All public service layer methods must have at least one JUnit test.

## User Stories
Total Points: 25

* As a user, I can log in.
    * 2 points
* As an admin, I can add a food item to the app.
    * 3 points
* As a customer, I can view the available food options and prices.
    * 1 point
* As a customer, I can add a food items to my order.
    * 3 points
* As an admin, I can edit or remove a food item.
    * 2 points
* As a customer, I can view my order before placing it.
    * 2 points
* As a customer, I can enter my address and place my order.
    * 3 points
* As a user, I can register for a customer account.
    * 3 points
* As a customer, I can edit or remove an item in my order.
    * 2 points
* As a customer, I can view my past orders.
    * 1 point
* As a customer, I can view my pending orders and mark them as delivered.
    * 1 point
* As an admin, I can view a history of all orders.
    * 1 point
* As the system, I can calculate the total cost of an order.
    * 1 point

## Bonus Stories
* As an admin, I can make delivery driver accounts.
* As a delivery driver, I can view all pending orders.
* As a delivery driver, I can mark a pending order as delivered.

## Bonus Technical Requirements
* An additional feature of your choice; for example:
    - Use a lambda/functional interface
    - Use a Stream
    - Implement password hashing
    - Use log4j to log to a file
    - Use Mockito for unit testing