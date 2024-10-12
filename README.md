# Variables and Data Types
Variables:
- Variables are used to store information for later use in your programs.
- You can assign values to variables using the `=` operator.
- Example:
- age = 23  # integer
  height = 5.8  # float
  name = "John Doe"  # string
  is_student = True  # boolean
  
# Basic Operations
Arithmetic Operations:
- Addition (`+`): `5 + 3` results in `8`
- Subtraction (`-`): `10 - 4` results in `6`
- Multiplication (`*`): `2 * 3` results in `6`
- Division (`/`): `8 / 2` results in `4.0`
  
# Data Structures: Lists and Dictionaries
- Lists: Ordered collections that can hold multiple values.
- Dictionaries: Key-value pairs (like a real-life dictionary, where you have words and their definitions).
- List example
fruits = ["apple", "banana", "cherry"]
print(fruits[0])  # Output: apple
- Dictionary example
student = {"name": "Alice", "age": 22, "major": "IT"}
print(student["name"])  # Output: Alice

# Conditionals (If-Else Statements)
Conditionals are used to make decisions based on a condition.
age = 18

if age >= 18:
    print("You are an adult.")
else:
    print("You are a minor.")
if age >= 18: is the condition being tested.
It checks if the value of age is greater than or equal to 18.
If the condition is true (i.e., if age is indeed 18 or older), the code inside the if block is executed print("You are an adult.")
f the condition is false (i.e., if age is less than 18), the code inside the else block is executed print("You are a minor.")


# Loops 
Loops are used to repeat actions multiple times.
For loop: Used to iterate over a sequence (like a list).
While loop: Repeats while a condition is true (Repeats as long as a condition is true.)
- For loop example
fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(fruit) # Output: apple, banana, cherry

- While loop example
count = 0
while count < 3:
    print("Counting:", count)
    count += 1  # Increases count by 1 each time
