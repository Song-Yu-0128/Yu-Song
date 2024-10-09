mixed_list = [1, "apple", 3.14, 42, "banana", 7.5, 100, "grape"]
integers_list = [item for item in mixed_list if isinstance(item, int)]
print(integers_list)
