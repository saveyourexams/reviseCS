# Inputs,Variables and outputs:
```
name = input("What is your hobby")
hobby = input("What is your name")
print("Hello " + name + ", I see you enjoy " + hobby + "!")
```
# Data types, Casting and Arithmetic:
```
num = int(input("Enter an integer"))
num +=num
print(num)
```
# Selection (If else and ELIF statements)
```
num = int(input("input thy num."))
if num % 2 == 0 and num % 5 == 0:
    print("True")
else:
    print("False")
```
# Count Controlled Iteration (For loops):
```
num = int(input("Enter the number of times"))
total = 0
for x in range(1, num + 1):
    total += x ** 2
print(total)
```
# Condition Controlled Iteration (While loops):
```
num = int(input("What number bro?"))
multiple = 1
total = 0
while total < 50:
    total += num
    multiple += 1
print(total)
```
# String Manipulation Methods
```
text = input()
result = ""
for char in text:
    if char not in result:
        result += char
print(result)
```
# Cumulative sum
```
N = int(input("Enter N: "))
total = 0
for i in range(1, N + 1):
    total += i
    print(total, end=" ")
```
# Sum until 0
```
total = 0
while True:
    num = int(input())
    if num == 0:
        break
    total += num
print(total)
```
# Check Divisibilty by 10
```
num = int(input())
if num % 10 == 0:
    print("Divisible")
else:
    print("Not Divisible")
```

# Day of the week
```
day_num = int(input("Enter day number (1-7): "))

if day_num == 1:
    print("Monday")
elif day_num == 2:
    print("Tuesday")
elif day_num == 3:
    print("Wednesday")
elif day_num == 4:
    print("Thursday")
elif day_num == 5:
    print("Friday")
elif day_num == 6:
    print("Saturday")
elif day_num == 7:
    print("Sunday")
else:
    print("not good nunber")
```
# Find the average of two
```
num1 = float(input("Enter firt number: "))
num2 = float(input("Enter second nmber: "))

average = (num1 + num2) / 2
print(average)
```
# Subtract 4 numbers
```
a = int(input())
b = int(input())
c = int(input())
d = int(input())

result = a - b - c - d
print(result)

```
