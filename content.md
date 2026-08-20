In programming, division can be performed on both integers and floating-point numbers. However, depending on which language and operators are used, one of two types of division may occur: integer division or floating-point division. Both types of division have their own use cases and behaviors and it is important to understand what type of division is being performed in a given context to understand both the numerical value which will be calculated and whether an integer or a float will be returned.

# Floating Point Division

Floating point division is an operation where the result is a floating-point number. For example:

* Dividing the float 7.5 by the float 1.5 gives the float 5.0
* Dividing the float -6.5 by the integer 2 gives the float -3.25
* Dividing the integer 7 by the float -2.0 gives the float -3.5
* Dividing the integer 9 by the integer 4 gives the float 2.25

# Integer Division

Integer division is an operation where the result is rounded to an integer. Different programming languages implement this in different ways. The two most common approaches are floor division and truncation division. Depending on the data types of the inputs and the language used, the final answer may be either an integer or a float.

## Floor Division

Floor division rounds the result down toward negative infinity. This means that for positive results, the fractional part is simply removed, but for negative results, the result is rounded further down. For example:

* Dividing the integer 9 by the integer 4 gives the value 2
* Dividing the integer -7 by the integer 3 gives the value -3
* Dividing the float 9.5 by the integer 4 gives the value 2
* Dividing the float -7.5 by the integer 3 gives the value -3

## Truncation Division

Truncation division rounds the result toward zero. This means that for both positive and negative results, the fractional part is simply removed, moving closer to zero. For example:

* Dividing the integer 9 by the integer 4 gives the value 2
* Dividing the integer -7 by the integer 3 gives the value -2
* Dividing the float 9.5 by the integer 4 gives the value 2
* Dividing the float -7.5 by the integer 3 gives the value -2

# Division by Zero

Division by zero is undefined in mathematics. Different programming languages handle this in different ways, often resulting in errors or exceptions when an attempt is made to divide by zero.
