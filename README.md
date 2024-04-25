Additional Task For SINE, COSE, TAN Graph - Explanation

Ex) 3*tan(2x+7)-4 

How to write my program? 

1. I want the expression to be equal to input.(“Give me an equation”).split("(") then this will result in **`['3 * tan', '2x + 7) -4 ']`**

2. I want to assign an expression2 that splits the second element of the expression then this will be **`['2x+7', '-4 ']`** I want to get the first element of the list by assigning an inside_parentheses so this will be result in 2x + 7

3. I want to extract the k term by assigning the length of expression2 to 0 so this will print -4
   
4. I want to print the expression0 so this will print 3 * tan

5. I want to print the expression.find because it’s checking whether there is a value of the coefficient a so this will print **`['3 ', ' tan']`**

6. I want to convert the value of a to a float so it will print 3.0
   
7. I want to split the inside_parenthesis at the character ‘x’ so this will print **`['2', '+7']`**
   
8. I want to check if the first element of the Inside_parentheses has a length of 0 and if it does then the b = 0 and it will print 2.0
   
9. I want to check if the second element of the Inside_parentheses has length of 0 and if it does then the h = 0 and it will print 3.5
    
10. I want to make a line that creates an evenly spaced value between -10 and 10, along with having a total of 400
    
11. I want to print the operation based on the given input and I am using the formula: **`( y = a * np.tan(b * (x + h)) + k)`** 

12. I want to remove the lines of asymptotes now so I will use this function: **`y[:-1][abs(np.diff(y)) > 10 ]`** = np.nan 

13. **`“y[:-1]”`** = Selects all the y expect the last one 

14. **`“np.diff(y)”`** = Calculates the difference between the elements in the y array 

15. **`“abs(np.diff(y)) > 10”`** = Checks with differences are greater than 10  

16. **`“y[:-1][abs(np.diff(y)) > 10]“`** = Applies the conditions when the difference is greater than 10 

17. **`“np.nan”`** = The assigns the variable as “NOT A NUMBER”

18. I want to plot for the x values and the y values on their own particular axis and then I will give the graph a title such as tan, cos or sine

19. I want to know finally plot for the x label and y label and then do plt.show()

How to use my program? 

20. Open your Python program and run the script
21. Enter a unique equation in the format provided ('sin(2x) + 1') when asked. Trigonometric functions such as "sin," "cos," or "tan" can be selected, and their variables (such as 22. "2x") can be specified 
23. Aftering entering the equation, click on return 
24. Based on the provided equation, the computer will create and display a plot of the function that illustrates the behavior of the function throughout the range of x-values from -10 to 10. The plot will be titled "Sine Function Plot" and will include the function name. To understand the behavior of the function, including its magnitude, frequency, phase shift, and vertical shift, analyze the plotted graph 

References: 
https://stackoverflow.com/questions/48015191/how-to-extrapolate-a-function-based-on-x-y-values 
https://www.studytonight.com/post/trigonometric-function-in-python 

