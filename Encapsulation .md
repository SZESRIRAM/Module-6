# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
```
class Rectangle:
    def __init__(self,length,width):
        self.__length=length
        self.__width=width
    def show(self):
        print(self.__length)
        print(self.__width)
    def get_length(self):
        return self.__length
    def get_width(self):
        return self.__width
obj=Rectangle(5,3)
obj.show()
```
## Output
<img width="294" height="138" alt="image" src="https://github.com/user-attachments/assets/1df09db8-f53b-4542-af6f-c681f933f29b" />


## Result
Thus, the given program has been executed successfully and encapsulation is implemented using private data members in Python.
