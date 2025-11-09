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

