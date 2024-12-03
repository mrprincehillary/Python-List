# Python-List
This is a python program to illustrate how you can work on with python list data types

# I want the program to do this,
Create an empty list called my_list.
Append the following elements to my_list: 10, 20, 30, 40.
Insert the value 15 at the second position in the list.
Extend my_list with another list: [50, 60, 70].
Remove the last element from my_list.
Sort my_list in ascending order.
Find and print the index of the value 30 in my_list.
# This the Output
output 
![image](https://github.com/user-attachments/assets/6edf01d5-d452-407c-957e-2877f9af6ea8)

![image](https://github.com/user-attachments/assets/9137331e-ccc2-4274-844a-fd19b089b280)
# The program code
# Create an empty list
my_list = []

# Append elements to my_list
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

# Insert the value 15 at the second position
my_list.insert(1, 15)

# Extend my_list with another list
my_list.extend([50, 60, 70])

# Remove the last element from my_list
my_list.pop()

# Sort my_list in ascending order
my_list.sort()

# Find and print the index of the value 30
index_of_30 = my_list.index(30)
print("Index of 30 in my_list:", index_of_30)

# Print the final list
print("Final my_list:", my_list)
