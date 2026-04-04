First repository
Budgeting app

budget = float(input("Enter your budget: "))
add_items = input("Do you want to add items to your shopping list? (y/n): ").lower()
if add_items == 'y':
    shopping_list = []
    while True:
        item_name = input("Enter the name of the item (or 'done' to finish): ")
        if item_name.lower() == 'done':
            break
        item_price = float(input(f"Enter the price of {item_name}: "))
        shopping_list.append((item_name, item_price))
    total_cost = sum(price for _, price in shopping_list)
    print(f"Total cost of your shopping list: ${total_cost:.2f}")   
    if total_cost > budget:
        print("You are over budget. Consider removing some items.")
    else:
        print("You are within your budget. Happy shopping!")

Give credit if used for anything
