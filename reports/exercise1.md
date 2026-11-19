# Bug reports for exercise1.py

Line: 3  
Problem: The condition checks for odd numbers instead of even numbers. It returns True when `n % 2 == 1`, which is for odd numbers, not even.  
Example: is_even(4) returns False, expected True.  
Fix: return n % 2 == 0

Line: 8  
Problem: The function adds width and height instead of multiplying them, which is incorrect for rectangle area.  
Example: rectangle_area(5, 3) returns 8, expected 15.  
Fix: return width * height

Line: 13  
Problem: The function adds 2 to n instead of doubling it.  
Example: double(5) returns 7, expected 10.  
Fix: return n * 2
