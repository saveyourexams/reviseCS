# Remove element by value
```
# get the lists
list1 = input("Enter list: ").split()
list2 = input("Enter item to remove: ").split()

# find common items
common = [x for x in list1 if x in list2]

if common:
    list3 = [x for x in list1 if x not in list2]
    print("Updated list:", " ".join(list3))
else:
    print("Item", list2[0], "not found in list.")
```
# Inset Element in Indix
```
# Get the list and input
items = input("Enter items:").split()
index = int(input("Enter:"))
new_item = input("Enter te nw itm: ")

# Insert the item
items.insert(index, new_item)

# Output the updated list
print("Updated list:", " ".join(items))

```
