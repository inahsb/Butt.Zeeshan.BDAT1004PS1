# Butt.Zeeshan.BDAT1004PS1
Problem Set 1
import math
def triangleArea(a, b, c):
    # Calculate semi-perimeter
    s = (a + b + c) / 2
    # Calculate area using Heron's formula
    area = math.sqrt(s * (s - a) * (s - b) * (s - c))
    return area
# Example usage
result = triangleArea(2, 2, 2)
print(result)
