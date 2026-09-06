# 1FA05---ILA-Programming-Activit
import math

x1 = float(input("Enter x1: "))
y1 = float(input("Enter y1: "))
x2 = float(input("Enter x2: "))
y2 = float(input("Enter y2: "))

distance = math.sqrt(math.pow(x2 - x1, 2) + math.pow(y2 - y1, 2))

print(f"\nThe distance between the two points is: {distance:.2f}")

# Reflection:
# Using a library is easier because it provides functions that make
# calculations easier. math.sqrt() and math.pow() simplify
# the distance formula instead of calculating everything from the beginning.
