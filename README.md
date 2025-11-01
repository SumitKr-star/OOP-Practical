# Python Practicals
# 1. Write a program to find the nature of the roots of a quadratic equation
<p># Quadratic Equation: ax^2 + bx + c = 0</p>
a = float(input("Enter coefficient a: "))<br>
b = float(input("Enter coefficient b: "))<br>
c = float(input("Enter coefficient c: "))<br>
<br>
# Calculate discriminant<br>
<p>D = b**2 - 4*a*c</p
print("Discriminant (D) =", D)<br>
<br>
# Nature of roots,<br>
<p>if D > 0:</p>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;print("The equation has real and distinct roots.")<br>
elif D == 0:<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;print("The equation has real and equal roots.")<br>
else:<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;print("The equation has imaginary (complex) roots.")</P>
