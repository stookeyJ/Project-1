Due Date: Friday, April 19
Objective:
	Control structures (if statement, loops), relational and logical operators, math functions.

A point on a plane is represented by two values: x and y. The values determine whether the point is on the origin, on the x-axis, y-axis, or one of the four quadrants.

 
Write a Python program that repeatedly prompts the user to input a point (values for x, and y). the two values represent an x-y coordinate. Your program should output a message followed by the point itself. Round the values of x and y to one decimal place.

Your program must also output the point’s distance from the origin (0,0). Round the distance to three decimal places.

Your program must contain a main() function that is called to start the program. Other than main(), it must have at least 3 other functions. One function (quadrant_check(p1, p2)) must take two coordinates and find what quadrant it is in. One function (find_distance(p1, p2))must take two coordinates and find the distance of the point from the origin. One function (cont()) must ask the user if they would like to continue by taking an input (‘y’ or ‘n’) and printing and error if they put anything else in. 

Sample input/output:
Enter the x coordinate: 3 
Enter the y coordinate: -4
The point is located in quadrant IV (3.0, -4.0)
The distance from the origin is:  5.0
Would you like to continue? (y/n) y
Enter the x coordinate: -1
Enter the y coordinate: 0
The point is located in the x-axis (-1.0, 0.0)
The distance from the origin is:  1.0
Would you like to continue? (y/n) y
Enter the x coordinate: 6.789
Enter the y coordinate: 4.321
The point is located in quadrant I (6.8, 4.3)
The distance from the origin is:  8.045
Would you like to continue? (y/n) n


Grading: Total = 40 Pts.
•	20 pts: Code is fully functional and has correct output.
•	8 pts: Program contains a main function, as well as at least 3 other functions (quadrant_check(p1, p2), find_distance(p1, p2), cont()).
•	6 pts: Code contains documentation/comments that explain the program.
•	3 pts: Program runs continuously without needing to be run every time.
•	3 pts: The output matches the requested format.
