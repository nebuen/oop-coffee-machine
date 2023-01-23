# Coffee Vending Machine Simulation - OOP

## Overview
This project simulates a coffee vending machine, where the user can order different types of coffee, pay for it, and the machine will check if the resources are sufficient and make the coffee if resources are sufficient and return the change. Additionally, it keeps track of the profit, resources, and money received.
<br />

<h2>Files</h2>

- <b> `menu.py` : This file defines two classes `MenuItem` and `Menu` which are used to create a menu of drinks that can be ordered. The `MenuItem` class takes in a name, cost, water, milk, and coffee as input and creates an instance of a drink with those parameters. The `Menu` class creates a list of `MenuItem` instances as its menu and has a function `get_items()` that returns all the names of the available menu items, and a function `find_drink(order_name)` that takes an order_name as input and searches the menu for a drink with that name and returns that drink if it exists, otherwise it returns None..</b>

- <b> `money_machine.py` : This file defines a class `MoneyMachine` which is used to handle money transactions. It has a property `profit` which keeps track of the total profit and a property `money_received` which keeps track of the money received. It has a function `process_coins()` that prompts the user to insert coins and returns the total amount of money received, a function `make_payment(cost)` that takes the cost of the drink as input and checks if the money received is sufficient to purchase the drink. If the money is sufficient, it returns True and updates the profit, otherwise it returns False and refunds the money received.</b>


- <b> `coffee_maker.py` : This file defines a class `CoffeeMaker` which is used to make the coffee. It has a property `resources` which keeps track of the resources (water, milk, coffee) and a function `is_resource_sufficient`(drink) that takes a drink as input and checks if the resources are sufficient to make the drink and returns True if they are and False if they are not. It also has a function `make_coffee`(order) that takes an order as input and makes the coffee by deducting the required ingredients from the resources. </b>
- <b> `main.py` - is the entry point of the program. It imports the classes and functions from the other files and uses them to handle user input and interactions, such as prompting the user to choose a drink, checking resources, processing payment, and making the coffee. </b>


### This project demonstrates object-oriented programming concepts, such as encapsulation and abstraction, and the use of classes and objects to model real-world entities. It also involves file I/O, input validation, and error handling.

<p align="center">
Launch <br/>
<img src="https://imgur.com/wzNkLcF.png" height="80%" width="80%"/>
<br />
