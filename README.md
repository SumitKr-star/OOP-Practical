# Python Practicals
# 1. Write a program to find the nature of the roots of a quadratic equation
<p>#Quadratic Equation: ax^2 + bx + c = 0</p>

<p># Input coefficients</p>
a = float(input("Enter coefficient a: "))<br>
b = float(input("Enter coefficient b: "))<br>
c = float(input("Enter coefficient c: "))<br>
<br>
<p># Calculate discriminant</p>
D = b**2 - 4*a*c<br>
print("Discriminant (D) =", D)<br>
<br>
<p># Nature of roots,</p>
if D > 0:<br>
</pre>print("The equation has real and distinct roots.")<br>
elif D == 0:<br>
<pre>print("The equation has real and equal roots.")<br>
else:<br>
    print("The equation has imaginary (complex) roots.")

