# Python - More Classes and Objects

In this project, I practiced object-oriented programming in Python, exploring class methods, static methods, class vs instance attributes, and the use of special `__str__` and `__repr__` methods.

## Tests :heavy_check_mark:

* [tests](./tests): Holberton School-provided test files.

## Tasks :page_with_curl:

* **0. Simple rectangle**
  * [0-rectangle.py](./0-rectangle.py): An empty Python class defining a rectangle.

* **1. Real definition of a rectangle**
  * [1-rectangle.py](./1-rectangle.py): Python class defining a rectangle with width, height, and validation. Includes instantiation, width and height properties, and type/size validation.

* **2. Area and Perimeter**
  * [2-rectangle.py](./2-rectangle.py): Python class with methods for area and perimeter calculations. Deals with special cases where width or height is zero.

* **3. String representation**
  * [3-rectangle.py](./3-rectangle.py): Python class with a special `__str__` method for a more readable rectangle string representation.

* **4. Eval is magic**
  * [4-rectangle.py](./4-rectangle.py): Python class with a special `__repr__` method for string representation, allowing recreation of the object.

* **5. Detect instance deletion**
  * [5-rectangle.py](./5-rectangle.py): Python class with a special `__del__` method that prints a message when a rectangle instance is deleted.

* **6. How many instances**
  * [6-rectangle.py](./6-rectangle.py): Python class with a class attribute tracking the number of instances. Updates on instantiation and deletion.

* **7. Change representation**
  * [7-rectangle.py](./7-rectangle.py): Python class with a class attribute for changing the string representation symbol. Default is `#`.

* **8. Compare rectangles**
  * [8-rectangle.py](./8-rectangle.py): Python class with a static method to compare rectangles based on area. Handles type checking.

* **9. A square is a rectangle**
  * [9-rectangle.py](./9-rectangle.py): Python class with a class method to create a square instance, where width and height are the same.

* **10. N Queens**
  * [101-nqueens.py](./101-nqueens.py): Python program solving the N queens puzzle, providing solutions for placing N non-attacking queens on an NxN chessboard. Validates input, checks for solutions, and prints the solutions in a specified format.
