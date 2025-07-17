🎉 Fun Calculator 🎉
Welcome to the Fun Calculator – your friendly Python-powered math buddy! With just a few lines of code, you can add, subtract, multiply, and divide any two numbers (including decimals) in style. 😎

🚀 What Does This Calculator Do?
Prompts you to enter two numbers (decimals or whole numbers).

Calculates:

➕ Sum

➖ Difference

✖️ Product

➗ Quotient

Displays the results with a sprinkle of fun!

📝 How to Run
Copy the code below into a file called fun_calculator.py:

python
# 🎉 Welcome to the Fun Calculator! 🎉

# Step 1: Ask the user to input the first number
num1 = float(input("Enter the first number: "))

# Step 2: Ask the user to input the second number
num2 = float(input("Enter the second number: "))

# Step 3: Do some math!
sum_result = num1 + num2
difference_result = num1 - num2
product_result = num1 * num2
quotient_result = num1 / num2  # (Assumes num2 isn't zero)

# Step 4: Show the results
print(f"Results of your two numbers:")
print(f"Sum: {sum_result}")         # ➕
print(f"Difference: {difference_result}")   # ➖
print(f"Product: {product_result}")         # ✖️
print(f"Quotient: {quotient_result}")       # ➗
Open your terminal and navigate to the directory where you saved the file.

Run the calculator with:

text
python fun_calculator.py
Follow the prompts, enter two numbers, and get your results!

⚠️ Note
If you enter 0 as the second number, Python will throw a ZeroDivisionError. For now, the calculator assumes you enter sensible numbers!

🛠️ How it Works
User Input: Asks for two numbers using float() for decimal support.

Calculations: Adds, subtracts, multiplies, and divides the numbers.

Results: Prints each result to the screen.

💡 Want to Improve It?
Add error handling for division by zero.

Make the user choose which operation to perform.

Loop so the user can do multiple calculations without restarting the program!

📚 Who is this For?
Perfect for Python beginners who want to practice user input, arithmetic, and print statements—while having fun! 🎈

Happy calculating! 💻✨
