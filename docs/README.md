
# Math formulas


| Figure      | Circle                          | Rectangle                                        | Square                                      | Triangle                                                                                        |
|-------------|---------------------------------|--------------------------------------------------|---------------------------------------------|-------------------------------------------------------------------------------------------------|
| Parameters  | $r$ --- *radius of the circle.* | $a, b$ --- *lengths of sides of the rectangle.*  | $a$ --- *length of the side of the square.* | $a, b, c$ --- *lengths of the sides of the triangle; h - length of the height of the triangle.* |
| Area        | $πr²$                           | $ab$                                             | $a²$                                        | $ah/2$                                                                                          |
| Perimeter   | $2πr$                           | $2a + 2b$                                        | $4a$                                        | $a + b + c$                                                                                     |





# Description of functions

## Circle
Parameter $r$ --- $int$ or $float$.
The calculated value always has type $float$.

### Examples
```py
circle.perimeter(1)
# 6.283185307179586

circle.area(1)
# 3.141592653589793

circle.perimeter(0.5)
# 3.141592653589793
```

## Rectangle
Parameters $a, b$ --- $int$ or $float$.
The calculated value can be $int$ or $float$.

### Examples
```py
rectangle.area(2, 3)
# 6

rectangle.perimeter(2, 3)
# 10

rectangle.area(1.5, 4)
# 6.0
```

## Square
Parameter $a$ --- $int$ or $float$.
The calculated value can be $int$ or $float$.

### Examples
```py
area(2)
# 4

area(2.5)
# 6.25

perimeter(3.5)
# 14.0
```

## Triangle
Parameters $a, b, c, h$ --- $int$ or $float$.
Area value can always has type $float$.
Perimeter value can be $int$ or $float$

### Examples
```py
triangle.area(1, 2)
# 1.0

triangle.area(2.5, 3.5)
# 4.375

triangle.perimeter(10, 20, 20)
# 50
```

# Tests

## test_circle.py
Contains the CircleTestCase class responsible for testing circle.area() and circle.perimeter().

## test_rectangle.py
Contains the RectangleTestCase class responsible for testing rectangle.area() and rectangle.perimeter().

## test_square.py
Contains the SquareTestCase class responsible for testing square.area() and square.perimeter().

## test_triangle.py
Contains the TriangleTestCase class responsible for testing triangle.area() and triangle.perimeter().
