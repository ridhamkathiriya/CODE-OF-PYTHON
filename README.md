# CODE-OF-PYTHON
#FUNCTION OF LIST
# Creating a list
my_list = [5, 2, 8, 1, 3]
print("Original List:", my_list)

# 1. Accessing elements
print("First element:", my_list[0])
print("Last element:", my_list[-1])

# 2. Modifying elements
my_list[1] = 10
print("After modifying second element:", my_list)

# 3. Adding elements
my_list.append(7)               # Add at the end
print("After append:", my_list)

my_list.insert(2, 20)           # Insert at index 2
print("After insert:", my_list)

# 4. Removing elements
my_list.remove(10)              # Remove value 10
print("After remove:", my_list)

# 5. Searching and counting
print("Index of 7:", my_list.index(7))   # Find index of value
print("Count of 7:", my_list.count(7))   # Count occurrences

# 6. Sorting 
my_list.sort()                  # Sort ascending
print("Sorted list:", my_list)

# 7. Length, max, min, sum
print("Length:", len(my_list))
print("Max:", max(my_list))
print("Min:", min(my_list))
print("Sum:", sum(my_list))

# 9. Slicing
print("Slice (1 t
