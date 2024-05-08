# Python Fundamentals

## Comments
You can leave notes for yourself or other readers in your code by using comments. They operate within your code as small reminders or explanatory notes because the computer does not execute them.

e.g. `#This is a comment`

## Variables
Consider variables as informational storage units. They have the capacity to store a variety of data, including words, figures, and even entire sentences. So that you can refer to that data later in your code, you give them a name. In Python we use the equals sign to store values into variables. 
e.g. 
``` 
a = 1 
b = 2
```

## Data Types
The types of information that your variables can store are categorised by data types. They consist of text (strings), numbers (integers and decimals), and booleans, which represent true or false values.
e.g.
```
a = "this is a sentence" #this is a string
b = 1 #this is an integer
c = 1.5 #this is a float
d = True #this is a boolean
```
## Numbers and Math Operators
Math operators are symbols like +, -, *, and / that allow you to conduct calculations with numbers in your code. Numbers are just what they sound like: digits.
e.g. 
```
a = 1 
b = 2
c = a + b
print(c) #this asks Python to print the value of c
3 #This would be the resutl from the above print statement
```
## Boolean and Equality Operators
Booleans represent two values: true or false. Equality operators like == and != help you compare values and decide if they're the same or different.
e.g. 
```
# Using equality operators to compare values
a = 5
b = 7

# Checking if two numbers are equal
if a == b:
    print("The numbers are equal.")
else:
    print("The numbers are not equal.")

# Checking if two numbers are not equal
if a != b:
    print("The numbers are not equal.")
else:
    print("The numbers are equal.")
```
## String Methods
Strings are sequences of characters, like words or sentences. String methods are built-in functions that let you manipulate strings, like changing their case or finding specific words within them. e.g.
```
message = "hello, world!"

# Changing case
print(message.upper())   # Output: HELLO, WORLD!
print(message.capitalize())   # Output: Hello, world!

# Finding specific words
print(message.find("world"))   # Output: 7

# Replacing characters
print(message.replace("world", "Python"))   # Output: hello, Python!
```
## Concatenation
Concatenation means joining things together. In Python, it's often used with strings to combine them into one longer string. e.g.
```
first_name = "John"
last_name = "Doe"

full_name = first_name + " " + last_name # Concatenating first name and last name

print(full_name)   # Output: John Doe
```

## Lists
 Lists are collections of items, like a shopping list or a list of friends' names. You can store any kind of data in a list and easily access or modify its elements. e.g.
```
shopping_list = ["apples", "bananas", "bread", "milk"]

# Accessing elements
print(shopping_list[0])   # Output: apples
print(shopping_list[-1])    # Output: milk

# Modifying elements
shopping_list[1] = "oranges" # Output: shopping_list = ["apples", "oranges", "bread", "milk"]

# Adding elements
shopping_list.append("eggs") # Output: ["apples", "oranges", "bread", "milk", "eggs"]

# Removing elements
removed_item = shopping_list.pop(2) #Output: ["apples", "oranges", "milk", "eggs"]

```

## Dictionaries
Dictionaries are like real-life dictionaries – they contain pairs of keys and values. You use a key to look up its associated value, just like you'd look up a word in a dictionary to find its definition. e.g.

```
word_definitions = {
    "apple": "a round fruit with red or green skin and a whitish inside",
    "banana": "a long curved fruit with a soft yellow flesh",
    "carrot": "a long, orange vegetable that grows in the ground"
}

# Accessing values using keys
print("Meaning of 'apple':", word_definitions["apple"])

# Adding a new word and its meaning
word_definitions["grape"] = "a small, sweet fruit that grows in clusters"

# Modifying the meaning of an existing word
word_definitions["banana"] = "a long curved fruit with a yellow skin and a sweet flavor"

# Removing a word and its meaning
del word_definitions["carrot"]
```

## For Loops
For loops are handy for repeating a block of code a certain number of times or for each item in a collection (like a list). They help you automate repetitive tasks in your code.
```
# Printing numbers from 1 to 5
for i in range(1, 6):
    print(i) 
#Output: 1, 2, 3, 4, 5
```

## While Loops
While loops keep running a block of code as long as a certain condition is true. They're useful when you don't know exactly how many times you need to repeat something. e.g.
```
# Example of while loop
count = 0
while count < 5:
    print("Count:", count)
    count += 1
# This will print the count and then increment it by 1, once it reaches 5 the while statement will not longer be True so the loop will stop. 
```

## Conditional Statements
Conditional statements let your code make decisions. They check if a condition is true or false, and then execute different code blocks accordingly.
```
# Example of conditional statements
x = 10
if x > 5:
    print("x is greater than 5")
else:
    print("x is not greater than 5")
#Output: x is greater than 5
```

## Functions
Functions are like little machines that take input, do something with it, and then give you output. They help you organize your code and avoid repeating the same steps over and over. e.g. 
```
def add_numbers(a, b): #define function name and arguments
    return a + b

result = add_numbers(3, 5) #This calls the function and stores the result in a variable called "result"
print("Result:", result)
#Output: Result: 8 
```
















# HEADING 1
## HEADING 2
### HEADING 3

*word* <br>
**word**

##Bullet Points
- Bullet 1
- Bullet 2

* Bullet 1
    * sub bullet
* Bullet 2
    * subbullet


1. one
   2. test
   3. test
2. two
3. three

## Code Snippets and Blocks
snippet:
`code snippet`
Use " ` " wrap

This is a very long sentence that I am writing to test the line wrap thing. 

Code Block:
``` 
This is a whole arse code block!!!!!!!!!!!!!!!
Message = "Hello world!"
print(message)
```

You can create a code block by using 3 back ticks blud 

## Images and links

