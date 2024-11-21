Simple Python Input/Output Program
This program demonstrates basic input and output operations in Python, including user interaction, string formatting, and arithmetic calculations.

Features
Prompts the user to enter their name and age.
Greets the user and displays their age.
Asks the user for two numbers and calculates their sum.
Displays the sum in multiple formats.
How It Works
User Interaction:

The program asks for the user's name and age.
It displays a personalized greeting using the entered name.
Arithmetic Operations:

The user is prompted to input two numbers.
The program calculates and prints the sum of the two numbers.
Output Variations:

The result is printed both as a formatted string and as a raw output.
How to Run the Program
Make sure Python (version 3.6 or above) is installed on your system.
Save the Python script with a .py extension, e.g., program.py.
Open a terminal or command prompt.
Run the script using the following command:
bash
Copy code
python program.py
Code
python
Copy code
# Get user's name and display a greeting
name = input("Enter your name: ")
print("How are you Mr. " + name + ". Have a good day")

# Get user's age
age = input("Enter your age: ")

# Display user's age and another greeting
name = input("Enter your name again: ")
print("Your age is: " + age)
print("How are you Mr. " + name + " Have a good day")

# Arithmetic operations
a = int(input("Put a number: "))
b = int(input("Put another number: "))
s = a + b

# Display the summation
print("Summation is: " + str(s))  # Using string concatenation
print("Summation is: ", s)       # Using comma-separated output
print(s)                         # Raw output
Expected Input/Output
Example 1:
Input:

mathematica
Copy code
Enter your name: John
How are you Mr. John. Have a good day
Enter your age: 25
Enter your name again: John
Output:

yaml
Copy code
Your age is: 25
How are you Mr. John Have a good day
Put a number: 10
Put another number: 15
Summation is: 25
Summation is:  25
25
Common Issues
Invalid Input:

Entering non-numeric values for a or b will cause a ValueError. Ensure only numbers are provided.
String Concatenation Errors:

Make sure to convert numeric values to strings when concatenating them with other strings using +.
