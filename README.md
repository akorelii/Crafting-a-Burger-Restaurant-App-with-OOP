# Crafting-a-Burger-Restaurant-App-with-OOP

Bill runs a fast-food hamburger restaurant and sells hamburger meals.
His meal orders are composed of three items: the hamburger, the drink, and the side item.
The challange is to write an app to let Bill select the type of burgers and some of the additional items or extras that can be added to the burgers, as well as the actual pricing.

**Meal Order:**
-This should be composed of exactly one burger, one drink, and one side item.
-The most common meal order should be created without any arguments, like a regular burger, a small coke, and fries, for example.
-You should be able to create other meal orders by specifying different burgers, drinks, and site items.

**Drink and Side Item:**
-The drink should have at least a type, size, and price, and the price of the drink should change for each size.
-The side item needs at least a type and price.

**Burgers:**
-Every hamburger should have a burger type, a base price, and up to a maximum of three extra toppings.
-The constructor should include only the burger type and price
-Extra Toppings on a burger need to be added somehow and priced according to their type.

**The Deluxe Burger bonus:**
-Create a deluxe burger meal eith a deluxe burger that has a set price, so that any additional toppings do not change the price.
-The Deluxe Burger should have room for an additional two toppings.


**Main method should have code to do the following:**
-Create a defauld meal that uses the nı arguments constructor.
-Create a meal with a burger and drink and side item of your choice, with up to 3 extra toppings.
-Create a meal with a deluxe burger where all items, drink, side item, and up to 5 extra toppings are included in the burger price.

For each meal orde, you'll want to perform these functions:
-Add some aditional toppings to the burger.
-Change the size of the drink.
-Print the itemized list. This should include the price of the burger, any extra toppings, the drink price based on size, and the side item price.
-Pring the total due amount for the meal.
