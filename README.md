Day-01
BASIC OF PYTHON
👉PYTHON is developed by Guido van rossum
Python is a high level language which is used to translate given source code to machine level  language..
😊 Python use interpreter..
●Python is simple & easy
●Free and open source 
●High level language 
●portabal 


😌Python Character set
●letters -A to Z,a to z
●Digits-0 to 9
●special symbol: -,+,*,/etc
●whitespaces-Blank Space,tab,carriage return,newline,form feed
●other character-Python can process all ASCII and Unicode characters as part of data or literals...


😁1st program 
print("hello world")


😇Types of operators 

An operator is a symbol that performs a certain  operation between operands..
●Arthmetic Operators (+,-,*,/,%,**)
●Relation/comparison operator(==,!=,<,>,>=,<=)
●Assignment operators(=,+=,-=,*=,/=,%=,**=)
●Logical operator(not,and,or)
●Bithwise operator

OOP: classes, objects, methods, inheritance
Explain these in depth.

Sure. Since you’re revising Python OOP, I’ll explain Classes, Objects, Methods, and Inheritance from beginner level to interview/exam level, with simple examples.



Task-02

ADVANCED PYTHON....

OOP in Python
OOP = Object-Oriented Programming

OOP is a programming approach where we organize a program around objects and classes.

Real-world example:

Student → class

Shweta → object

Student's name, age → attributes

Student studying → method/behavior

The four topics you asked about are:

Class

Object

Methods

Inheritance

1. Class
Definition
A class is a blueprint or template for creating objects.

Think of a class as a design/template.

For example, if we want to represent students:

class Student:
    name = "Shweta"
    age = 18
Here, Student is a class.

It describes what a student object can have.

Syntax
class ClassName:
    # attributes
    # methods
Example:

class Student:
    name = "Shweta"
    age = 18
Here:

class → keyword

Student → class name

name → attribute

age → attribute

Why do we need a class?
Suppose you have 100 students.

Without OOP, you might write:

student1_name = "Shweta"
student1_age = 18

student2_name = "Rahul"
student2_age = 19
This becomes difficult to manage.

Using a class:

class Student:
    pass
Now we can create many student objects from the same class.

student1 = Student()
student2 = Student()
student3 = Student()
The class provides the common structure.





