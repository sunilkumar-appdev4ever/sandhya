# sandhya
# Define the two lists
list1 = ["a", "b", "c", "d", "e", "f", "g", "h", "i", "j"]
list2 = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

# Combine the lists by concatenating corresponding elements
combined_list = [f"{x}{y}" for x, y in zip(list2, list1)]

# Output the combined list
print(combined_list)
