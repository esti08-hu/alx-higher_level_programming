 # Python - Inheritance

This project demonstrates the concepts of inheritance in Python, including class inheritance, super- and sub-classes, multiple base classes, and overriding inherited methods and attributes.

## Files and Structure

The project consists of several Python files, each containing functions and classes related to inheritance. Here's a brief overview of the files and their contents:

- `0-lookup.py`: Contains a function that returns a list of available attributes and methods of an object.

- `1-my_list.py`: Defines a custom Python class `MyList` that inherits from the built-in `list` class. It includes a method `print_sorted` that prints the list in ascending sorted order.

- `2-is_same_class.py`: Contains a function that checks if an object is exactly an instance of a specified class.

- `3-is_kind_of_class.py`: Contains a function that checks if an object is an instance or inherited instance of a specified class.

- `4-inherits_from.py`: Contains a function that checks if an object is an inherited instance (either directly or indirectly) from a specified class.

- `5-base_geometry.py`: Defines an empty Python class `BaseGeometry`.

- `6-base_geometry.py`: Extends the `BaseGeometry` class with a method `area` that raises an `Exception` when called.

- `7-base_geometry.py`: Further extends the `BaseGeometry` class with a method `integer_validator` that validates a given integer value.

- `8-rectangle.py`: Defines a `Rectangle` class that inherits from `BaseGeometry`. It includes private attributes `width` and `height`, validated using `integer_validator`, and an initializer method `__init__`.

- `9-rectangle.py`: Extends the `Rectangle` class with an implementation of the `area` method and a `__str__` method for printing rectangles in a specific format.

- `10-square.py`: Defines a `Square` class that inherits from `Rectangle`. It includes a private attribute `size`, validated using `integer_validator`, and an initializer method `__init__`.

- `11-square.py`: Extends the `Square` class with a `__str__` method for printing squares in a specific format.

- `100-my_
