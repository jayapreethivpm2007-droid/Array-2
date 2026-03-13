Delete an Element
Python:

# List ADT using array - Delete element

arr = [10, 20, 30, 40, 50]

print "Original List:", arr

x = int(raw_input("Enter element to delete: "))

if x in arr:
    arr.remove(x)
    print "List after deletion:", arr
else:
    print "Element not found"

Output Example:

Original List: [10, 20, 30, 40, 50]
Enter element to delete: 30
List after deletion: [10, 20, 40, 50]
