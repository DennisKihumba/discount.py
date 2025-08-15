# 🧮 Discount Calculator

This Python script calculates the final price of an item after applying a discount. It only applies the discount if it's **20% or higher**—otherwise, the original price is returned.

## 📌 Features

- Prompts the user to enter:
  - Original price of the item
  - Discount percentage
- Applies the discount only if it's **≥ 20%**
- Displays the final price with or without discount
- Handles invalid input gracefully using `try-except`

## 🧠 Logic Overview

```python
if discount_percent >= 20:
    apply discount
else:
    return original price
```

## 🚀 How to Run

1. Make sure you have Python installed (version 3.x recommended).
2. Save the script as `discount_calculator.py`.
3. Run it in your terminal or IDE:

```bash
python discount_calculator.py
```

4. Enter the original price and discount percentage when prompted.

## 🧪 Example

```text
Enter the original price of the item: 100
Enter the discount percentage: 25
Discount applied! Final price: $75.00
```

```text
Enter the original price of the item: 100
Enter the discount percentage: 10
No discount applied. Final price remains: $100.00
```

## ⚠️ Error Handling

If the user enters non-numeric input, the program will display:

```text
Please enter valid numeric values for price and discount.
```

## 🛠️ Customization Ideas

Want to take it further? Here are a few enhancements you could try:
- Add currency formatting or localization
- Support bulk item discounts
- Build a GUI with Tkinter or a web form with Flask
- Log transactions to a file or database

