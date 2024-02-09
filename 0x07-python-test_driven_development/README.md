```markdown
# Python - Test-driven development

![alt text](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-higher-level_programming+/246/giphy-4.gif)

This project focuses on test-driven development using `docstring` and `unittest` in Python.

## Tests :heavy_check_mark:

* [tests](./tests): Folder containing test files, including Holberton-provided and eight independently-developed tests.

## Function Prototypes :floppy_disk:

Prototypes for functions written in this project:

| File                     | Prototype                                    |
| ------------------------ | -------------------------------------------- |
| `0-add_integer.py`       | `def add_integer(a, b=98):`                  |
| `2-matrix_divided.py`    | `def matrix_divided(matrix, div):`           |
| `3-say_my_name.py`       | `def say_my_name(first_name, last_name=""):` |
| `4-print_square.py`      | `def print_square(size):`                    |
| `5-text_indentation.py`  | `def text_indentation(text):`                |
| `100-matrix_mul.py`      | `def matrix_mul(m_a, m_b):`                  |
| `101-lazy_matrix_mul.py` | `def lazy_matrix_mul(m_a, m_b):`             |
| `102-python.c`           | `void print_python_string(PyObject *p);`     |

## Tasks :page_with_curl:

* **0. Integers addition**
  * [0-add_integer.py](./0-add_integer.py): Python function that returns the integer addition of two numbers.
  * Handles type checking and casting.

* **1. Divide a matrix**
  * [2-matrix_divided.py](./2-matrix_divided.py): Python function that divides all elements of a matrix by a common divisor.
  * Handles matrix validation and division, raising appropriate errors.

* **2. Say my name**
  * [3-say_my_name.py](./3-say_my_name.py): Python function that prints a name in the format `My name is <first_name> <last_name>`.
  * Handles type checking.

* **3. Print square**
  * [4-print_square.py](./4-print_square.py): Python function that prints a square using the `#` character.
  * Handles size validation.

* **4. Text indentation**
  * [5-text_indentation.py](./5-text_indentation.py): Python function that prints text with indentation.
  * Handles type checking and indentation logic.

* **5. Max integer - Unittest**
  * [tests/6-max_integer_test.py](./tests/6-max_integer_text.py): Python class/script that runs unittests for the function `def max_integer(list=[]):`.

* **6. Matrix multiplication**
  * [100-matrix_mul.py](./100-matrix_mul.py): Python function that multiplies two matrices.
  * Handles matrix validation and multiplication, raising appropriate errors.

* **7. Lazy matrix multiplication**
  * [101-lazy_matrix_mul.py](./101-lazy_matrix_mul.py): Python function for matrix multiplication using NumPy.
  * Identical in function to [100-matrix_mul.py](./100-matrix_mul.py).

* **8. CPython #3: Python Strings**
  * [102-python.c](./102-python.c): C function printing information about Python string objects.
```