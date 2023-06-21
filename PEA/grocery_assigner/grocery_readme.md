# Grocery Assigner

This program assigns grocery items to different persons based on the given prompts. The prompts consist of two CSV string data: `grocery_list` and `person_list`. The `grocery_list` contains information about the items, stores, weights, and prices, while the `person_list` contains the names of the persons.

## Input

The input for this program consists of the following prompts:

1. `[Grocery list]` - A CSV string representing the grocery items. The CSV format should have the following columns: `Items`, `Store`, `Weight`, and `Price`. Each row represents a specific grocery item with its corresponding details.

2. `[Persons list]` - A CSV string containing the names of the persons who need to be assigned grocery items. Each row represents a person's name.

## Output

The program will generate the following output:

1. CSV Text: The assigned grocery items will be presented as a CSV text. This text will include the original columns from the `grocery_list` CSV, along with an additional column, `'Assigned Person Name'`. The items will be grouped by the shop name.

2. Tabular Representation: The assigned grocery items will be displayed in tabular form using Markdown. The table will include the columns from the `grocery_list` CSV, as well as the `'Assigned Person Name'` column. The items will be grouped by the shop name.

## Usage

To use this program, follow these steps:

1. Provide the grocery items information in CSV format using the `[Grocery list]` prompt. The CSV should include the columns `Items`, `Store`, `Weight`, and `Price`. Each row represents a specific grocery item.

2. Provide the names of the persons in CSV format using the `[Persons list]` prompt. Each row represents a person's name.

3. The program will process the input and generate the assigned grocery items.

4. The assigned grocery items will be presented as a CSV text, including the additional `'Assigned Person Name'` column. The items will be grouped by the shop name.

5. The assigned grocery items will also be displayed in tabular form using Markdown. The table will include the columns from the `grocery_list` CSV, as well as the `'Assigned Person Name'` column. The items will be grouped by the shop name.

## Example

### Input

```
[Grocery list]:
Items,Store,Weight,Price
Apples,Grocery Store A,2,2.99
Bananas,Grocery Store B,1,1.49
Milk,Grocery Store A,4,3.99
Bread,Grocery Store C,2,2.49

[Persons list]:
PersonName
John
Jane
```

### Output

```
CSV Text:
Items,Store,Weight,Price,Assigned Person Name
Apples,Grocery Store A,2,2.99,John
Bananas,Grocery Store B,1,1.49,Jane
Milk,Grocery Store A,4,3.99,John
Bread,Grocery Store C,2,2.49,Jane

Tabular Representation:

| Items  | Store            | Weight | Price | Assigned Person Name |
|--------|------------------|--------|-------|---------------------|
| Apples | Grocery Store A  | 2      | 2.99  | John                |
| Bananas| Grocery Store B  | 1      | 1.49  | Jane                |
| Milk   | Grocery Store A  | 4      | 3.99  | John                |
| Bread  | Grocery Store C  | 2      |

 2.49  | Jane                |
```

In this example, two persons, John and Jane, were assigned grocery items from the provided list. Each person has been assigned items from different shops, maintaining a uniform distribution based on item weight as much as possible. The assigned grocery items are then presented in both CSV text and tabular form using Markdown.