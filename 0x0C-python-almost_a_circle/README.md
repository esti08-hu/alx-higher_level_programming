# Python - Almost a circle

![Circle](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-higher-level_programming+/331/giphy.mp4)

In this project, I applied Python object-oriented programming skills to code three connected classes representing rectangles and squares. I created a test suite using the `unittest` module to thoroughly test each class's functionality.

## Tests :heavy_check_mark:

* [tests/test_models](./tests/test_models): Folder containing independently-developed test files:
  * [test_base.py](./tests/test_models/test_base.py)
  * [test_rectangle.py](./tests/test_models/test_rectangle.py)
  * [test_square.py](./tests/test_models/test_square.py)

## Classes :cl:

### Base
Represents the "base" class for all other classes in the project. Includes:

* Private class attribute `__nb_objects = 0`.
* Public instance attribute `id`.
* Class constructor `def __init__(self, id=None):`
  * If `id` is `None`, increments `__nb_objects` and assigns its value to the public instance attribute `id`.
  * Otherwise, sets the public instance attribute `id` to the provided `id`.
* Static method `def to_json_string(list_dictionaries):` that returns the JSON string serialization of a list of dictionaries.
  * If `list_dictionaries` is `None` or empty, returns the string `"[]"`.
* ... (other methods)

### Rectangle
Represents a rectangle. Inherits from `Base` with:

* Private instance attributes `__width`, `__height`, `__x`, and `__y`.
  * Each private instance attribute features its own getter/setter.
* Class constructor `def __init__(self, width, height, x=0, y=0, id=None):`
  * ... (validation checks)
* Public method `def area(self):` that returns the area of the `Rectangle` instance.
* ... (other methods)

### Square
Represents a square. Inherits from `Rectangle` with:

* Class constructor `def __init__(self, size, x=0, y=0, id=None):`
  * ... (assignment of width and height)
* ... (other methods)
