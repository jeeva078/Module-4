# Ex.No:4A CLASS AND OBJECTS - AREA OF RECTANGLE

## AIM  
To Write a Python class named Rectangle constructed by a length and width, has 2 methods 1. setvalues - to set the values of length and breadth ,2. a method which will compute the area of a rectangle.

## ALGORITHM
1. Begin the program.
2. Define a class Rectangle with two methods: setvalues(self, length, width) to set the length and width of the rectangle,area(self) to calculate and return the area of the rectangle (length * width).
3. Use input() to get the values for length and width from the user.
4. Create an object rect of the Rectangle class.
5. Call the setvalues() method to set the values of length and width.
6. Call the area() method and print the result.
7. Terminate the program.

## PROGRAM
```
class Rectangle:
    def setvalues(self, length, width):
        self.length = length
        self.width = width

    def area(self):
        return self.length * self.width


# Taking input from the user
length = int(input())
width = int(input())

rect = Rectangle()
rect.setvalues(length, width)
print(rect.area())
```
## OUTPUT
![Screenshot 2025-04-27 161934](https://github.com/user-attachments/assets/f1067eab-9331-4a88-a193-4536ac16c042)

## RESULT
Thus a Python class named Rectangle constructed by a length and width has been successfully implemented.
