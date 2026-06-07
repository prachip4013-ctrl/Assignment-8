# Assignment-8
Open In Colab

d = {'a': 3, 'b': 1, 'c': 2}

asc = dict(sorted(d.items(), key=lambda x: x[1]))
desc = dict(sorted(d.items(), key=lambda x: x[1], reverse=True))

print("Ascending:", asc)
print("Descending:", desc)
     
Ascending: {'b': 1, 'c': 2, 'a': 3}
Descending: {'a': 3, 'c': 2, 'b': 1}

d = {'a': 1, 'b': 2}
key = input("Enter key: ")

if key in d:
    print("Key exists")
else:
    print("Key does not exist")
     
Enter key: a
Key exists

d1 = {'a': 1, 'b': 2}
d2 = {'c': 3, 'd': 4}

d1.update(d2)
print("Merged dictionary:", d1)
     
Merged dictionary: {'a': 1, 'b': 2, 'c': 3, 'd': 4}

t = (1, 2, 3)
new_item = int(input("Enter item: "))

t = t + (new_item,)
print("Updated tuple:", t)
     
Enter item: 5
Updated tuple: (1, 2, 3, 5)

t = (1, "Hello", 3.5, True)
print("Tuple:", t)
     
Tuple: (1, 'Hello', 3.5, True)

lst = list(map(int, input("Enter numbers: ").split()))
print("Sum:", sum(lst))
     
Enter numbers: 66
Sum: 66

lst = list(map(int, input("Enter numbers: ").split()))
print("Largest number:", max(lst))
     
Enter numbers: 5 2 9 1 
Largest number: 9

s = {1, 2, 3}
num = int(input("Enter number to add: "))
s.add(num)

print("Updated set:", s)
     
Enter number to add: 4
Updated set: {1, 2, 3, 4}

arr = list(map(int, input("Enter numbers: ").split()))
arr.reverse()

print("Reversed array:", arr)
     
Enter numbers: 6 7 8 9 
Reversed array: [9, 8, 7, 6]

arr = []

for i in range(5):
    num = int(input(f"Enter element {i}: "))
    arr.append(num)

print("Array:", arr)

index = int(input("Enter index to access: "))
print("Element at index:", arr[index])
     
Enter element 0: 10
Enter element 1: 20
Enter element 2: 30
Enter element 3: 40
Enter element 4: 50
Array: [10, 20, 30, 40, 50]
Enter index to access: 2
Element at index: 30
