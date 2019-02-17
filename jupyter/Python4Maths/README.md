<small><small><i>
This course is almost directly copied from the below repository. Only minor modifications have been made.

Introduction to Python - available from https://gitlab.erc.monash.edu.au/andrease/Python4Maths.git

The original version was written by Rajath Kumar and is available at https://github.com/rajathkumarmp/Python-Lectures.
The notes have been updated for Python 3 and amended for use in Monash University mathematics courses by [Andreas Ernst](http://users.monash.edu.au/~andreas)
</small></small></i>

# Python-Lectures

## Introduction

Python is a modern, robust, high level programming language. It is very easy to pick up even if you are completely new to programming.

Python, similar to other languages like matlab or R, is interpreted hence runs slowly compared to C++, Fortran or Java. However writing programs in Python is very quick. Python has a very large collection of libraries for everything from scientific computing to web services. It caters for object oriented and functional programming with module system that allows large and complex applications to be developed in Python.

These lectures are using jupyter notebooks which mix Python code with documentation. The python notebooks can be run by clicking the link or stand-alone on a computer.

To give an indication of what Python code looks like, here is a simple bit of code that defines a set $N=\{1,3,4,5,7\}$ and calculates the sum of the squared elements of this set: $$\sum_{i\in N} i^2=100$$


```python
N={1,3,4,5,7}
print('The sum of ∑_i∈N i*i =',sum( i**2 for i in N ) )
```

    The sum of ∑_i∈N i*i = 100


## Contents

This course is broken up into a number of notebooks (chapters).

* [01](https://mybinder.org/v2/gh/Data-to-Knowledge/Hydrosoc-python-2018.git/master?filepath=jupyter%2FPython4Maths%2FIntro-to-Python%2F01.ipynb) Basic data types and operations (numbers, strings)
* [02](https://mybinder.org/v2/gh/Data-to-Knowledge/Hydrosoc-python-2018.git/master?filepath=jupyter%2FPython4Maths%2FIntro-to-Python%2F02.ipynb) String manipulation
* [03](https://mybinder.org/v2/gh/Data-to-Knowledge/Hydrosoc-python-2018.git/master?filepath=jupyter%2FPython4Maths%2FIntro-to-Python%2F03.ipynb) Data structures: Lists and Tuples
* [04](https://mybinder.org/v2/gh/Data-to-Knowledge/Hydrosoc-python-2018.git/master?filepath=jupyter%2FPython4Maths%2FIntro-to-Python%2F04.ipynb) Data structures (continued): dictionaries
* [05](https://mybinder.org/v2/gh/Data-to-Knowledge/Hydrosoc-python-2018.git/master?filepath=jupyter%2FPython4Maths%2FIntro-to-Python%2F05.ipynb) Control statements: if, for, while, try statements
* [06](https://mybinder.org/v2/gh/Data-to-Knowledge/Hydrosoc-python-2018.git/master?filepath=jupyter%2FPython4Maths%2FIntro-to-Python%2F06.ipynb) Functions
* [07](https://mybinder.org/v2/gh/Data-to-Knowledge/Hydrosoc-python-2018.git/master?filepath=jupyter%2FPython4Maths%2FIntro-to-Python%2F07.ipynb) Classes and basic object oriented programming


This is a tutorial style introduction to Python. For a quick reminder / summary of Python syntax the following [Quick Reference Card](http://www.cs.put.poznan.pl/csobaniec/software/python/py-qrc.html) may be useful. A longer and more detailed tutorial style introduction to python is available from the python site at: https://docs.python.org/3/tutorial/


## License
This work is licensed under the Creative Commons Attribution 3.0 Unported License. To view a copy of this license, visit http://creativecommons.org/licenses/by/3.0/
