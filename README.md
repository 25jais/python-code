# Creating a tuple
my_tuple = (1, 2, 3, 4, 5)

# Accessing elements of a tuple
print("First element:", my_tuple[0])
print("Last element:", my_tuple[-1])

# Tuple is immutable, so we can't add or remove elements
# However, we can concatenate or slice tuples to create new tuples

# Concatenating tuples
new_tuple = my_tuple + (6, 7)
print("Concatenated tuple:", new_tuple)

# Slicing tuple
sliced_tuple = my_tuple[2:4]
print("Sliced tuple:", sliced_tuple)

# Iterating through the tuple
print("Iterating through the tuple:")
for item in my_tuple:
    print(item)
/////////////////////////////////////////////
# Creating a list
my_list = [1, 2, 3, 4, 5]

# Accessing elements of a list
print("First element:", my_list[0])
print("Last element:", my_list[-1])

# Adding an element to the list
my_list.append(6)
print("List after appending 6:", my_list)

# Removing an element from the list
my_list.remove(3)
print("List after removing 3:", my_list)

# Iterating through the list
print("Iterating through the list:")
for item in my_list:
    print(item)
///////////////////////////////////
# Creating a dictionary
my_dict = {'name': 'John', 'age': 30, 'city': 'New York'}

# Accessing elements of a dictionary
print("Name:", my_dict['name'])
print("Age:", my_dict['age'])

# Adding a new key-value pair to the dictionary
my_dict['gender'] = 'Male'
print("Dictionary after adding gender:", my_dict)

# Removing a key-value pair from the dictionary
del my_dict['city']
print("Dictionary after removing city:", my_dict)

# Iterating through the dictionary
print("Iterating through the dictionary:")
for key, value in my_dict.items():
    print(key, ":", value)
