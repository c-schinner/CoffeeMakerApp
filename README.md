# Coffee Maker App
The Coffee Maker App is a simple command-line program that simulates a coffee maker machine. Users can choose from a menu of coffee options, insert coins to pay for their chosen drink, and receive their ordered coffee. The app also tracks the machine's resources and profit.

# Features
Menu: The app offers three types of coffee:

Espresso
Latte
Cappuccino
Each coffee type has its own set of ingredients and cost associated with it.

Resource Management: The app keeps track of the following resources required to make coffee:

Water (in milliliters)
Milk (in milliliters)
Coffee (in grams)
The available resources are displayed when the user requests a machine report.

Transaction: Users can insert coins to pay for their selected coffee. The app accepts pennies, nickels, dimes, and quarters. If the payment is sufficient, the app calculates the change to return to the user and updates the profit accordingly.

Making Coffee: When a user's order is successful, the app deducts the required resources from the machine's inventory and serves the selected coffee.

Machine Report: Users can request a machine report that displays the current available resources (water, milk, coffee) and the total profit earned by the machine.

Turning Off: The app can be turned off by typing "off" in the input prompt.

# How to Use
Run the coffee_maker_app.py script in a Python interpreter.

The available coffee options and their prices will be displayed.

Enter your choice of coffee by typing "espresso," "latte," or "cappuccino."

If you wish to check the machine's resources, type "report."

To turn off the app, type "off."

When you select a coffee, the app will prompt you to insert coins. Enter the number of pennies, nickels, dimes, and quarters you wish to insert.

If the payment is successful, the app will serve your coffee and return any change.

# Notes
Make sure to provide valid inputs as specified in the prompts to avoid errors.
The app doesn't have persistent memory; it starts fresh every time you run it.
The resources required for each coffee type are predefined and cannot be customized within the app.
The app is designed for demonstration purposes and does not handle edge cases or complex scenarios.

# License
This Coffee Maker App is provided under the MIT License. Feel free to modify and distribute it according to the terms of the license.

Enjoy your virtual coffee-making experience with the Coffee Maker App! If you have any questions or suggestions, feel free to reach out to the app's creator.
