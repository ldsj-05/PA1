# PA1
Leah Jones 
I collaborated with my TA's  
CS480
Programming Assignment 1 
This code includes using Bresenham's algorithm for scanline fill and line algorithms. I have added the drawLine function to draw a line between two points that the user pressed. When smooth shading is on, it interpolates the color of the line. I have added the drawTriangle function, which fills a triangle based on three right clicks a user inputs. 

Variables and Data Structures 
Point: point with coordinates and colors 
Colortype: stores colors: red, green, blue 
Buff: Pixel that stores the image 
doSmooth: smooth color interpolation
doAA: anti-aliasing

Error 
Two functions I have added include checks to avoid dividing by zero to help with problems with colors and coordinates. File loading condition that currently has no use, but I wanted to keep in as I was trying to implement it and wanted to show it. Mouse-click the condition so the computer only draws a line or fills a triangle if a condition is met. 

Mistakes/Problems 
I had trouble naming my files and was not able to give my code its original name due to many problems within my system. I had problems loading the image even when using the direct directory pathway. 

Websites I used for help
https://stackoverflow.com/
https://www.geeksforgeeks.org/bresenhams-line-generation-algorithm/
https://babavoss.pythonanywhere.com/python/bresenham-line-drawing-algorithm-implemented-in-py
https://www.youtube.com/watch?v=yaovJmM-0OM
