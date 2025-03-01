```python
x=input(int("cuantos años tienes")
print(x)
```


      Cell In[1], line 1
        x=input(int("cuantos años tienes")
               ^
    SyntaxError: '(' was never closed
    



```python
print(s)
```


    ---------------------------------------------------------------------------

    NameError                                 Traceback (most recent call last)

    Cell In[3], line 1
    ----> 1 print(s)
    

    NameError: name 's' is not defined



```python
print("ejemplo"+1)
```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    Cell In[5], line 1
    ----> 1 print("ejemplo"+1)
    

    TypeError: can only concatenate str (not "int") to str



```python
import foo
```


    ---------------------------------------------------------------------------

    ModuleNotFoundError                       Traceback (most recent call last)

    Cell In[29], line 1
    ----> 1 import foo
    

    ModuleNotFoundError: No module named 'foo'



```python
import math
print(math.squar(4))
```


    ---------------------------------------------------------------------------

    AttributeError                            Traceback (most recent call last)

    Cell In[57], line 2
          1 import math
    ----> 2 print(math.squar(4))
    

    AttributeError: module 'math' has no attribute 'squar'



```python
my_list = [1, 2, 3]
print(my_list[5])
```


    ---------------------------------------------------------------------------

    IndexError                                Traceback (most recent call last)

    Cell In[53], line 2
          1 my_list = [1, 2, 3]
    ----> 2 print(my_list[5])
    

    IndexError: list index out of range



```python
my_dict = {'a': 1, 'b': 2}
print(my_dict['c'])
```


    ---------------------------------------------------------------------------

    KeyError                                  Traceback (most recent call last)

    Cell In[55], line 2
          1 my_dict = {'a': 1, 'b': 2}
    ----> 2 print(my_dict['c'])
    

    KeyError: 'c'



```python
if True:
print("no se")
```


      Cell In[49], line 2
        print("Esto debería estar indentado")
        ^
    IndentationError: expected an indented block after 'if' statement on line 1
    



```python
number = int("abc")
```


    ---------------------------------------------------------------------------

    ValueError                                Traceback (most recent call last)

    Cell In[51], line 1
    ----> 1 number = int("abc")
    

    ValueError: invalid literal for int() with base 10: 'abc'



```python
x = 10 / 0
```


    ---------------------------------------------------------------------------

    ZeroDivisionError                         Traceback (most recent call last)

    Cell In[59], line 1
    ----> 1 x = 10 / 0
    

    ZeroDivisionError: division by zero



```python

```
