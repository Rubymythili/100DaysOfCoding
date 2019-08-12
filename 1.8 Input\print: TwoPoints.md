## First calculate in your own head, what should be the distance? 
## What changes to the logic will you make it to match 5? 

```
Look at the first test case - Point p1 = (0,0) and Point p2 =(4,0). If you mentally apply your mind, the answer is 4. Write the simple formula for this and past the test case.
Look at the second test case - Point p1 = (4,0) and Point p2 = (0,0). The answer should again be 4. But what does your code calculate the value to? What is the one simple change you will do to make it pass Test case 1 and Test case 2?
Now consider two points on the Y-axis, say (0, 2) and (0, 4). What additional line of code will you write to tackle this?
And then comes the complex one: What if the points are (0, 0) and (4, 3)?
 ```
 
 ```
 Example 

INPUT 
4
0
0
0

OUTPUT
4

INPUT 
0
0
4
3

OUTPUT
5

 ```
 
 ```
 # get the x coordinate of Point 1
x1 = int(input())  
# get the y coordinate of Point 2
y1 = int(input())  
# get the x coordinate of Point 2
x2 = int(input())
# get the y coordinate of Point 2
y2 = int(input())

# Write the code to calculate distance between the two points 
distance =  ( ( ((x2 - x1) ** 2) + ((y2  - y1) ** 2) ) ** 0.5 )
  
#print value 
print(distance)
 ```
