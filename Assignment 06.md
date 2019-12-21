```python
# Question 01

Object-oriented programming (OOP) is a programming language model in which programs are organized around data,
or objects, rather than functions and logic. An object can be defined as a data field that has unique attributes and 
behavior. Examples of an object can range from physical entities, such as a human being that is described by properties 
like name and address, down to small computer programs, such as widgets.
```


```python
# Question 02

The advantages of object-oriented programming lie in this kind of encapsulation.
1. Modularity for easier troubleshooting
2. Reuse of code through inheritance
3. Flexibility through polymorphism
4. Effective problem solving
5. OOP languages allows you to break down your software into bite-sized problems 
   that you then can solve — one object at a time.
```


```python
# Question 03

Function:
A function is a piece of code that is called by name.
It can be passed data to operate on (i.e. the parameters) and can optionally return data (the return value). 
All data that is passed to a function is explicitly passed.

Method:
A method is a piece of code that is called by a name that is associated with an object.
```


```python
# Question 04

1. Class: Classes in object-oriented programming, a class is a blueprint for creating objects.
    (a particular data structure), providing initial values for state (member variables or attributes), 
    and implementations of behavior (member functions or methods). 
    The user-defined objects are created using the class keyword.
    
2. Object: In object-oriented programming (OOP), are the units of code that are eventually derived from the process.
    Each object is an instance of a particular class or subclass with the class's own methods or procedures and 
    data variables.
    
3. Attribute: Attributes are data stored inside a class or instance and represent the state or quality of the class 
    or instance. In short, attributes store information about the instance.
    
4. Behaviour: The behavior of an object is defined by its methods, which are the functions and subroutines defined
    within the object class. Without class methods, a class would simply be a structure. Methods determine what 
    type of functionality a class has, how it modifies its data, and its overall behavior.
```


```python
# Question 05

#class
class Car():
    #instantiation method
    def __init__(self, model, color, name, company, rate):
        #attributes and attributes name
        self.model = model
        self.color = color
        self.name = name
        self.company = company
        self.rate = rate
    #method 1 
    def say_if_old(self):
        if int(self.model) < 2019:
            print("This is old model")
        else:
            print("This is the latest model")
    #method 2
    def say_if_not_in_color(self):
        if self.color == 'Black':
            print("Not available !")
        else:
            print("Available !")
        
    #method 3
    def out_of_rate(self):
        if int(self.rate) > 100:
            print("Out Of rate")
        else:
            print("With in rate")
        
        
# Instances        
c1 = Car('2018', 'White', 'Civic', 'Honda', '40')
c2 = Car('2016', 'Black', 'Cultus', 'Suzuki', '18')
c3 = Car('2019', 'Gun Metallic', 'Corolla', 'Toyota', '42')
c4 = Car('2017', 'Red', 'Mecedees', 'Mercedeed', '90')
c5 = Car('2019', 'Mate Black', 'Jaguar', 'BMW', '150')

#printing results

#Car1 details:
print("Car 1 details:")
print(c1.name)
print(c1.model)
print(c1.color)
print(c1.company)
print(c1.rate," lac")
c1.say_if_old()
c1.say_if_not_in_color()
c1.out_of_rate()
print("\n")

#Car2 details:
print("Car 2 details:")
print(c2.name)
print(c2.model)
print(c2.color)
print(c2.company)
print(c2.rate," lac")
c2.say_if_old()
c2.say_if_not_in_color()
c2.out_of_rate()
print("\n")

#Car3 details:
print("Car 3 details:")
print(c3.name)
print(c3.model)
print(c3.color)
print(c3.company)
print(c3.rate," lac")
c3.say_if_old()
c3.say_if_not_in_color()
c3.out_of_rate()
print("\n")

#Car4 details:
print("Car 4 details:")
print(c4.name)
print(c4.model)
print(c4.color)
print(c4.company)
print(c4.rate," lac")
c4.say_if_old()
c4.say_if_not_in_color()
c4.out_of_rate()
print("\n")

#Car5 details:
print("Car 5 details:")
print(c5.name)
print(c5.model)
print(c5.color)
print(c5.company)
print(c5.rate," lac")
c5.say_if_old()
c5.say_if_not_in_color()
c5.out_of_rate()
print("\n")

    
    
    
```

    Car 1 details:
    Civic
    2018
    White
    Honda
    40  lac
    This is old model
    Available !
    With in rate
    
    
    Car 2 details:
    Cultus
    2016
    Black
    Suzuki
    18  lac
    This is old model
    Not available !
    With in rate
    
    
    Car 3 details:
    Corolla
    2019
    Gun Metallic
    Toyota
    42  lac
    This is the latest model
    Available !
    With in rate
    
    
    Car 4 details:
    Mecedees
    2017
    Red
    Mercedeed
    90  lac
    This is old model
    Available !
    With in rate
    
    
    Car 5 details:
    Jaguar
    2019
    Mate Black
    BMW
    150  lac
    This is the latest model
    Available !
    Out Of rate
    
    
    


```python

```
