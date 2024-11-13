# Item Purchase and Recommendation System

This repository implements an item purchase and recommendation system using association rule mining. The system suggests additional items to users based on the items they have purchased, leveraging association rules derived from the dataset.

## Features

- **Item Purchase:** Display a list of available items for users to select from.
- **Recommendation System:** Based on the items selected, the system recommends additional products using association rules.
- **Association Rule Mining:** The system uses the Apriori algorithm to generate frequent itemsets and derive association rules based on criteria like lift, support, and confidence.

## Data

The dataset contains information about various products across different categories such as beverages, vegetables, fruits, and more. The dataset is processed to extract frequent itemsets and generate association rules for recommendations.

## Requirements

- Python 3.x
- `pandas`
- `mlxtend` (for Apriori algorithm and association rule mining)
- `numpy`

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/item-recommendation-system.git
   cd item-recommendation-system
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the main script to start the recommendation system:

   ```bash
   python recommendation_system.py
   ```

2. Follow the prompts to select the items you have purchased, and the system will provide item recommendations based on the association rules.

## Example

The system provides a list of available items for purchase:

```
1. Tropical Fruit
2. Pip Fruit
3. Apple
4. Banana
5. Whole Milk
6. Yogurt
7. UHT-Milk
8. Soda
9. Bottled Beer
10. Beverages
11. Other Vegetables
12. Potato
13. Cabbage
14. Rolls/Buns
15. Beef
16. Berries
```

If the user selects items 8 (Soda) and 15 (Beef), the system may recommend the following:

```
- Bottled Water
- Rolls/Buns
- Shopping Bags
- Whole Milk
- Pastry
- Yogurt
- Other Vegetables
- Bottled Beer
- Sausage
```

## Author

This project is made by SYED ALI JIBRAN RIZVI.
