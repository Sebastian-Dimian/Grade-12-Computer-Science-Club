#  Object Oriented Programming


![Markdown Logo](https://i.ytimg.com/vi/SzJ46YA_RaA/maxresdefault.jpg)

## __Understanding__

- Normally an object is a variable, data structure, function or method.
- However object oriented programming is a instance of a class where the object can be either a variable, function, data structure or combination
- OOP focuses on how to manipulate the data of the object rather then the logic required to manipulate them.


## __Example code__

```python
class Dog:
  def __init__(self, given)name, breed, age):
      self.__name = given_name
      self.__breed = breed
      self.__age = age
```
1. The fist code line, ```class Dog``` is used like a template or blueprint for creating objects within the variable name ```Dog```
    1. *note* The first letter of the variable name ```Dog``` has to be capitalized
2. The next line is where you define and give your argument. Always start with the key word  ```self```. The reason you always use self, is so you can always call back to the code
3. The next three lines of code are all attributes that you are creating. Within the attributes you also notice two underscore lines, this is known as encapsulation. Encapsulation is used to restrict people from accessing the classes/objects.


## __concepts__

**Setter:** A setter updates an objects attribute value when the object is under encapsulation

**Getter:** A getter retrieves an object's correct attribute value when the object is under encapsulation

**Polymorphism:** Methods that are used in different classes that have same or different behavior

**Overloading:** Overloading is an illegal code in python. Overloading is when you have to methods in the same class with same name and parameters

**Overriding:** Overriding is when you have two methods in different classes with the same name and parameters


## __Example code 2__
```Python
def __str__str__(self):
    return f'User:{self.username}'
    
def __repr__(self):
    return self.__str__()
```
1. The first defined function is used a way to override the string built in method
    1. The formatting of the code here, ```f'User:{self.username}'``` is called formatted string literals or f-strings. This is where you start with letter "f" or "F" and contain the your variable within a curly bracket
2. The second defined function is used to present a printable version of object
    1. This topic can go more in depth so you can read more here, [wikpedia source on repr](https://docs.python.org/3/library/functions.html#repr)
