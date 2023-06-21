# Grocery List Manager

Welcome to the Grocery List Manager! This application allows you to manage a grocery list with various entities and their attributes. The goal is to assign each item to a person for purchase in such a way that the total weights of items assigned to each person are nearly equal. The output will provide a sorted list by shop, displaying items with the properly assigned person names.

## Instructions

The grocery list entities have the following attributes:

1. **Item name**: The name of the item. (String)

2. **Person name**: The person to whom the item is assigned for purchase.

3. **Shop name**: The shop from where the item is to be purchased by the assigned person.

4. **Price**: The price of the item.

5. **Weight**: The weight of the item.

## Input

The initial input includes a list of people and a list of items with their attributes. Here's an example:

**Person List**:
- Person1
- Person2
- Person3

**Item List**:
- {item_name: 'Banana', person_name: 'unassigned', shop_name: 'Shoppers', price: $5, weight: 500g}
- {item_name: 'Apple', person_name: 'unassigned', shop_name: 'Green Grocers', price: $3, weight: 300g}
- {item_name: 'Mango', person_name: 'unassigned', shop_name: 'Fruit Paradise', price: $8, weight: 700g}
- {item_name: 'Grapes', person_name: 'unassigned', shop_name: 'Vineyard Fresh', price: $4, weight: 400g}
- {item_name: 'Watermelon', person_name: 'unassigned', shop_name: 'Farmers Market', price: $10, weight: 5kg}
- {item_name: 'Pineapple', person_name: 'unassigned', shop_name: 'Tropical Delights', price: $7, weight: 1kg}
- {item_name: 'Strawberries', person_name: 'unassigned', shop_name: 'Berry Bliss', price: $6, weight: 250g}
- {item_name: 'Blueberries', person_name: 'unassigned', shop_name: 'Berry Paradise', price: $9, weight: 300g}
- {item_name: 'Peach', person_name: 'unassigned', shop_name: 'Orchard Fresh', price: $4, weight: 350g}
- {item_name: 'Kiwi', person_name: 'unassigned', shop_name: 'Tropical Fruits', price: $3, weight: 200g}

## Output

Your task is to assign a person name to each item in the item list in such a way that each person is responsible for purchasing items with nearly the same total weights. The output will be a sorted list by shop, where each item will have the properly assigned person name.

Please note that the implementation details of how the assignment is performed are abstracted away, and the focus is on achieving nearly equal total weights for each person.

Feel free to interact with the Grocery List Manager to assign person names to items and organize your shopping list efficiently!

*Note: The Grocery List Manager is a simplified application for managing grocery lists and assigning items to people. It does not handle real-time data or make actual purchases. Its purpose is to demonstrate the assignment of items based on weights for a more balanced distribution among people.*