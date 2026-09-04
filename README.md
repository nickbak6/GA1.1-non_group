# Collaborative Code Development Project 
# multiply(a,b)
Multiplies two numbers and returns the product
Potential problem: Trying to multiply a str with an int
Example:multiply(3, 4). It returns 12
# subtract(a,b)
Subtracts b from a and returns the result
Potential problem: Invalid types(e.g subtracting strings from int)
Example:subtract(10, 4). It returns 6
# add(a,b)
adds 2 numbers and return their sum
Potential problems: if a string and a int are added up together
Example: add(2,3). It returns 5

# distance_from_zero(x)
Calculates the absolute distance of a number from zero by calling subtract.
Potential problems: Passing non-numeric types will raise a TypeError.
Example: distance_from_zero(-8). It returns 8