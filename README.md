# OOPs: Object oriented programming
OOPs is a method of structuring a program by bundling related properties and behaviors into individual objects.
![image](https://media.geeksforgeeks.org/wp-content/uploads/20230818181616/Types-of-OOPS-2.gif)
1. Class:
  a> Classes are created by keyword class.
  b> Attributes are the variables that belong to a class.
  c> Attributes are always public and can be accessed using the dot (.) operator. Eg.: Myclass.Myattribute

2. Object:
   An object consists of:
    > State: It is represented by the attributes of an object. It also reflects the properties of an object.
    > Behavior: It is represented by the methods of an object. It also reflects the response of an object to other objects.
    > Identity: It gives a unique name to an object and enables one object to interact with other objects.
#Example
     c vvvvvvvvvvvvvvvvvvvvvvvvvvvvv
     #A class is a collection of objects and contains the blueprints or the prototype from which the objects are being created. It is a logical entity that contains some attributes and methods. 

#creating a Class(Student):

class student:
  def __init__(self, name, age, sex, course):
    self.name = name
    self.age = age
    self.sex = sex
    self.course = course

##The object is an entity that has a state and behavior associated with it. It may be any real-world object like a mouse ,Integers, strings, floating-point numbers, even arrays, and dictionaries.

#Creating Object(s1):

s1 = student("Yuvraj Singh", "19", "Male", "Bsc" )

print(s1.name)
print(s1.age)
print(s1.sex)
print(s1.course)
