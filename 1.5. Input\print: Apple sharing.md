## N students take K apples and distribute them among each other evenly. The remaining (the indivisible) part remains in the basket. How many apples will each single student get? How many apples will remain in the basket?
## The program reads the numbers N and K. It should print the two answers for the questions above.

```
Example input
6
50

Example output
8
2
```

```
# Read the numbers:

n = int(input())
k = int(input())

# Example of division, integer division and remainder:
#print(k / n)    # example of division 

print(k // n)   # example of integer division
print(k % n)    # example of remainder calculation 

```
