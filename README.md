# Hotel-Mahal---Food-Ordering-System   
 
A Project For Ordering The Food From A Hotel     
 

Introduction       


This is a simple console-based food ordering system for a restaurant called "Hotel Mahal." The system allows customers to select items from various food categories, calculate their total bill, and print the final order summary. The available food categories include Veg Starters, Veg Food, Veg Drinks, Veg Desserts, Non-Veg Starters, Non-Veg Food, Non-Veg Drinks, and Non-Veg Desserts.

Features


Food Selection: Customers can select items from Veg and Non-Veg sections. They can choose to order from either section or both.

Menu Items: Each section contains multiple options with corresponding prices.

Bill Calculation: The program calculates the total bill based on the quantity of each selected item.

Summary: Once the customer finishes selecting items, a detailed summary of the ordered items along with their respective prices is displayed, along with the total amount to be paid.


Main Topics Covered


1. Classes and Objects

   
The program uses classes to model the restaurant and its features.

The Hotel class is responsible for the logic of the ordering system.

The Main class contains the entry point (main method) for running the application.

3. Methods

   
The program defines multiple methods for handling different parts of the process:

selectionOfFoodSection() - Guides the user to select the food section.

vegSection() and nonVegSection() - Handles item selection for the Veg and Non-Veg sections.

selectItems() - Allows users to choose multiple items and calculate their total.

getPriceForItem() - Returns the price of a selected item.

addSelectedItem() - Adds the selected item to the final order summary.

printTotalBill() - Displays the final bill after the user has finished ordering.


5. Data Structures

   
ArrayList: The selectedItems ArrayList stores the list of ordered items and their details (name, quantity, and total price).

Scanner: A Scanner object is used for user input, allowing the customer to make selections.


7. Switch-Case Statements

   
The program uses switch-case statements to handle different options for food categories and item selections.


9. Loops

    
A while loop is used to allow the customer to select multiple items within each category and repeatedly prompt them for input.


11. Conditionals

    
If-else statements are used to guide the user through selecting food sections and handling invalid input.


13. String Manipulation

    
The getItemName() method uses strings to return the names of items based on the user's selection.


Usage


To run the system:

Clone the repository or copy the code to your Java IDE.

Compile and run the Main class.

Follow the on-screen instructions to select food items and get the total bill.

Conclusion


This simple food ordering system demonstrates key Java concepts like classes, methods, conditionals, loops, and user input handling. It can be expanded further to include additional features like a database to store orders, dynamic pricing, or a GUI for better user interaction.
