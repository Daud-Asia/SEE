# 🎉 Fun Calculator 🎉

Welcome to the **Fun Calculator**! This is a beginner-friendly Python script that lets you add, subtract, multiply, and divide two numbers. It's interactive, easy to use, and packed with fun comments and emojis to make your coding experience enjoyable! 😎

## Features

- **Addition** ➕
- **Subtraction** ➖
- **Multiplication** ✖️
- **Division** ➗

Supports both whole numbers and decimals for extra flexibility! ✨

## How It Works

1. **Input Numbers:**  
   The calculator will ask you to enter two numbers. Both numbers can be integers or decimals.

2. **Calculations:**  
   It will then calculate the following:
   - Sum (Addition)
   - Difference (Subtraction)
   - Product (Multiplication)
   - Quotient (Division)

3. **Results Display:**  
   The results are displayed clearly, showing all four operations.

## Usage

### Requirements

- Python 3.x installed

### Running the Program

1. Save the code below into a file, for example `fun_calculator.py`.

2. Open your terminal or command prompt.

3. Run the script:
   ```bash
   python fun_calculator.py
   ```

4. Follow the prompts to enter your two numbers.

### Example Output

```
Enter the first number: 10
Enter the second number: 2
Results of your two numbers:
Sum: 12.0
Difference: 8.0
Product: 20.0
Quotient: 5.0
```

## Code

```python
# 🎉 Welcome to the Fun Calculator! 🎉
# We're going to add, subtract, multiply, and divide two numbers like a boss! 😎

# Step 1: Ask the user to input the first number
# We're using 'float()' to make sure our numbers can have decimals too. Fancy, right? ✨
num1 = float(input("Enter the first number: "))

# Step 2: Ask the user to input the second number
# Same trick here—using 'float()' for decimal magic! 🧙‍♂️
num2 = float(input("Enter the second number: "))

# Step 3: Time to do some math! 🧠 Let's compute the sum, difference, product, and quotient.

# Add the two numbers (Yay! Addition is the first step to fun!) ➕
sum_result = num1 + num2

# Subtract the second number from the first (Negative vibes, but necessary! 😜) ➖
difference_result = num1 - num2

# Multiply the two numbers (More bang for your buck! 💥) ✖️
product_result = num1 * num2

# Divide the first number by the second (Be careful with zero here, no math disasters! 😅) ➗
# We'll assume the user is being responsible and not dividing by zero for now!
quotient_result = num1 / num2

# Step 4: Show the user what we got! 🥳 Time for the big reveal! 🎉
print(f"Results of your two numbers:")
print(f"Sum: {sum_result}")  # ➕
print(f"Difference: {difference_result}")  # ➖
print(f"Product: {product_result}")  # ✖️
print(f"Quotient: {quotient_result}")  # ➗

# 🏁 And that's it! You've just made a mini-calculator! 😎💻
```

## Notes

- This calculator does **not** handle division by zero. Please enter a non-zero second number when dividing.
- Feel free to expand and customize the calculator for more features!

---

Happy calculating! 🥳
