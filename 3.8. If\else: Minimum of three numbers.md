## Given three integers, print the least of them.

```
Example input
5
3
7

Example output
3
```

```
# Read an integer:
num1 = int(input())
num2 = int(input())
num3 = int(input())

#calculation:

if( (num1 < num2) and (num1 < num3)):
  minimum = num1
elif((num2 < num1) and (num2 < num3)):
  minimum = num2
else :
  minimum = num3

# Print a value:
print(minimum)

```
