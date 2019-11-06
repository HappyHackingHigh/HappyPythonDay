#
```
# -*- coding: utf-8 -*-
```

```
## Python Docstring


https://stackoverflow.com/questions/3898572/what-is-the-standard-python-docstring-format


Google Style Python Docstrings

https://www.sphinx-doc.org/en/master/usage/extensions/example_google.html#example-google


'''
This is an example of Google style.

Args:
    param1: This is the first param.
    param2: This is a second param.

Returns:
    This is a description of what is returned.

Raises:
    KeyError: Raises an exception.
'''
"""

def demo():
    """函數的文件字串"""
    pass
    
print(demo.__doc__)

def swap(a,b):
    """
    swap(a,b)功能是.................
    """ 
    a,b = b,a
    return (a,b)

print(swap(3,5))
print(swap.__doc__)

```
