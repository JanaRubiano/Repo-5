# Repo-5

1.  Determine if a number corresponds to the ASCII code of a lowercase vowel .

```python
n : int
if chr(n)in "aeiou":
	print(True, "n corresponds to a lowercase vowel in ASCII")
else:
	print(False, "n does't correspond to a lowercase vowel in ASCII")

```

2. Determine whether the ASCII code for the first letter of a string with length 1 is even or not.

```python
string : str
if ord(string[0])%2 == 0:
	 print(True)
else:
	print(False)
``` 

3. Determine whether a character is a digit. (I checked the definition of digit, and digits are the integers from 0 to 9).

```python
character : int or float
if type(character) == int and 0 <= character <= 9:
	 print("character is a digit")
else:
	print("character is not a digit")
```

4.  Determine if a real number x is positive, negative or zero.

```python
x : int or float
if x == 0:
	print("El número x es el neutro para la suma")
elif x > 0:
	print("El numero x es positivo")
else:
	print("El número x es negativo")
```

5. Given the center and radious of a circle, determine if a point with coordinates (x, y) is inside the circle.

```python
r = int or float 
center_x : int or float
center_y : int or float
point_x : int or float
point_y : int or float

if ((center_x + point_x)**2) + ((center_y + point_y)**2) <= r:
	print("The point is within the circle")
else:
	print("The point is out of the circle")
```

6. Determine if three positive lengths (a, b, c) can form a triangle.

```python
a : int or float
b : int or float
c : int or float
if abs(b-c) < a < b+c:
	print(True)
else:
	print (False)
``` 
