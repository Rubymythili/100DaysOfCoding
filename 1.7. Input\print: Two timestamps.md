## Given two timestamps of the same day: a number of hours, minutes and seconds for both of the timestamps. The moment of the first timestamp happened before the moment of the second one. Calculate how many seconds passed between them.

```
Example input #1
1
1
1
2
2
2

Example output #1
3661

Example input #2
1
2
30
1
3
20

Example output #2
50
```

```
# Read  integers :
hour_1 = int(input())
minute_1 = int(input())
second_1 = int(input())

hour_2 = int(input())
minute_2 = int(input())
second_2 = int(input())

#calculation of seconds passed between them:
seconds_passed = ((hour_2 - hour_1)*3600)+((minute_2 - minute_1)*60)+(second_2 - second_1)

# Print a value:
print(seconds_passed)


```
