#Assigniment
<h1 align="center">🐍 Python Variables, Data Types & Type Casting</h1>

<p align="center">
A beginner-friendly guide covering Python variable naming rules, data types, 
type() function, type casting, and practical examples.
</p>

<br>

<h2>📌 Introduction</h2>

<p>
Python is a high-level, easy-to-learn programming language.  
In this document, we will learn about Python variables, rules for naming variables, 
data types, the <b>type()</b> function, and type casting with examples.
</p>

<br>

<h2>🧮 What is a Variable?</h2>

<p>
A variable is a name given to a memory location that stores a value.  
In Python, variables do not need explicit data type declaration.
</p>

<p><b>Example:</b></p>

<pre>
x = 10
name = "Haroon"
</pre>

<br>

<h2>📏 Rules for Naming Variables</h2>

<ul>
  <li>Variable name must start with a letter (a-z, A-Z) or underscore (_)</li>
  <li>It cannot start with a number</li>
  <li>It can contain letters, numbers, and underscores</li>
  <li>Spaces are not allowed</li>
  <li>Special symbols like @, #, $, % are not allowed</li>
  <li>Variable names are case-sensitive</li>
</ul>

<p><b>Valid Names:</b> age, _count, total_marks</p>
<p><b>Invalid Names:</b> 1num, total-marks, my name</p>

<br>

<h2>📦 Data Types in Python</h2>

<p>
Data type defines the type of value stored in a variable.
</p>

<table border="1" cellpadding="8">
  <tr>
    <th>Data Type</th>
    <th>Description</th>
    <th>Example</th>
  </tr>
  <tr>
    <td>int</td>
    <td>Integer numbers</td>
    <td>10, 25, -3</td>
  </tr>
  <tr>
    <td>float</td>
    <td>Decimal numbers</td>
    <td>3.14, 5.6</td>
  </tr>
  <tr>
    <td>str</td>
    <td>Text / String</td>
    <td>"Python"</td>
  </tr>
  <tr>
    <td>bool</td>
    <td>True or False</td>
    <td>True, False</td>
  </tr>
  <tr>
    <td>list</td>
    <td>Collection of items</td>
    <td>[1,2,3]</td>
  </tr>
  <tr>
    <td>tuple</td>
    <td>Immutable collection</td>
    <td>(1,2,3)</td>
  </tr>
  <tr>
    <td>dict</td>
    <td>Key-value pairs</td>
    <td>{"a":1}</td>
  </tr>
</table>

<br>

<h2>🔍 type() Function</h2>

<p>
The <b>type()</b> function is used to find the data type of a variable.
</p>

<p><b>Example:</b></p>

<pre>
x = 10
y = 3.5
name = "Python"

print(type(x))
print(type(y))
print(type(name))
</pre>

<p><b>Output:</b></p>

<pre>
&lt;class 'int'&gt;
&lt;class 'float'&gt;
&lt;class 'str'&gt;
</pre>

<br>

<h2>🔄 What is Type Casting?</h2>

<p>
Type casting means converting one data type into another data type.
</p>

<p><b>Common Type Casting Functions:</b></p>

<ul>
  <li>int()</li>
  <li>float()</li>
  <li>str()</li>
</ul>

<p><b>Example:</b></p>

<pre>
x = "10"
y = int(x)

print(y)
print(type(y))
</pre>

<br>

<h2>📝 Write a Program (WAP)</h2>

<p>
Write a program to take two numbers from the user and print their values and data types.
</p>

<pre>
num1 = input("Enter first number: ")
num2 = input("Enter second number: ")

print("Value of num1:", num1)
print("Type of num1:", type(num1))

print("Value of num2:", num2)
print("Type of num2:", type(num2))
</pre>

<p><b>Converted Version Using Type Casting:</b></p>

<pre>
num1 = int(input("Enter first number: "))
num2 = float(input("Enter second number: "))

print("Value:", num1, "Type:", type(num1))
print("Value:", num2, "Type:", type(num2))
</pre>

<br>

<h2>🎯 Conclusion</h2>

<p>
Understanding variables, data types, and type casting is fundamental in Python.  
These concepts help in writing efficient, readable, and error-free programs.
</p>

<br>

<hr>

<p align="center">
⭐ If you find this helpful, give the repository a star!
</p>
