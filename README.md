# Arithmetic operations script
a = 10
b = 5

# Addition
sum_ab = a + b
print(f"Sum of {a} and {b} is: {sum_ab}")

# Subtraction
diff_ab = a - b
print(f"Difference of {a} and {b} is: {diff_ab}")

# Multiplication
prod_ab = a * b
print(f"Product of {a} and {b} is: {prod_ab}")

# Division
div_ab = a / b
print(f"Division of {a} by {b} is: {div_ab}")

# Integer Division (floor division)
div_ab_int = a // b
print(f"Integer division of {a} by {b} is: {div_ab_int}")

# Modulus
mod_ab = a % b
print(f"Modulus of {a} by {b} is: {mod_ab}")

# Exponentiation
exp_ab = a ** b
print(f"{a} raised to the power of {b} is: {exp_ab}")

# String manipulation script
string1 = "Hello,"
string2 = "world!"

# Concatenation
concatenated_string = string1 + " " + string2
print("Concatenated string:", concatenated_string)

# Length of string
length_string1 = len(string1)
print(f"Length of '{string1}' is: {length_string1}")

# String slicing
substring = string2[0:3]
print(f"Substring of '{string2}' from index 0 to 2 is: {substring}")

# Uppercase and lowercase
uppercase_string1 = string1.upper()
lowercase_string2 = string2.lower()
print(f"Uppercase of '{string1}' is: {uppercase_string1}")
print(f"Lowercase of '{string2}' is: {lowercase_string2}")

# Check if substring exists
if 'world' in concatenated_string:
    print("'world' is present in the concatenated string.")
else:
    print("'world' is not present in the concatenated string.")
# Conditional statements script
number = 15

# Check if number is even or odd
if number % 2 == 0:
    print(f"{number} is even.")
else:
    print(f"{number} is odd.")

# Check if number is positive, negative, or zero
if number > 0:
    print(f"{number} is positive.")
elif number < 0:
    print(f"{number} is negative.")
else:
    print(f"{number} is zero.")

# Nested conditional statement
grade = 85

if grade >= 90:
    print("Grade is A")
elif grade >= 80:
    print("Grade is B")
elif grade >= 70:
    print("Grade is C")
elif grade >= 60:
    print("Grade is D")
else:
    print("Grade is F")
////list list
# Creating a list
fruits = ['apple', 'banana', 'cherry', 'date']

# Accessing elements
print("First fruit:", fruits[0])
print("Last fruit:", fruits[-1])

# Slicing
print("Sliced fruits:", fruits[1:3])

# Modifying elements
fruits[1] = 'blueberry'
print("Modified list:", fruits)

# Adding elements
fruits.append('elderberry')
print("After appending:", fruits)

# Removing elements
removed_fruit = fruits.pop(2)
print("After popping:", fruits)
print("Removed fruit:", removed_fruit)

# Length of the list
print("Length of list:", len(fruits))

# Iterating over elements
print("Iterating over list:")
for fruit in fruits:
    print(fruit)
//dictionary
# Creating a dictionary
person = {
    'name': 'John Doe',
    'age': 30,
    'city': 'New York',
    'email': 'john.doe@example.com'
}

# Accessing values by keys
print("Name:", person['name'])
print("Age:", person['age'])

# Modifying values
person['age'] = 32
print("Updated age:", person['age'])

# Adding new key-value pairs
person['phone'] = '555-1234'
print("After adding phone:", person)

# Removing a key-value pair
removed_email = person.pop('email')
print("After removing email:", person)
print("Removed email:", removed_email)

# Length of the dictionary
print("Number of items in dictionary:", len(person))

# Iterating over keys and values
print("Iterating over dictionary:")
for key, value in person.items():
    print(key + ":", value)
////////////tuple////////
# Creating a tuple
coordinates = (3, 5)

# Accessing elements
print("X coordinate:", coordinates[0])
print("Y coordinate:", coordinates[1])

# Length of the tuple
print("Length of tuple:", len(coordinates))

# Iterating over elements
print("Iterating over tuple:")
for coordinate in coordinates:
    print(coordinate)
