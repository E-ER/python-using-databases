# Notes from Week 1
Week 1 is a quick overview of objects in Python.
To create new objects first write a Class, then you can create instances of objects in that Class.
## Class syntax
    class Dog:
        name = ""
        breed = ""
        
        # The init method defines what happens when an instance of the class is created
        def __init__(self, name, breed):
            self.name = name
            self.breed = breed
        
        def bark(self):
            print "Woof Woof!"

## Creating and working with instances of the Class
To create instances of the Dog class:

    >>> a = Dog("Harry", "Collie")
    >>> b = Dog("Henry", "Labrador")

Then attributes and methods can be accessed:

    >>> a.name
    Harry
    >>> b.breed
    Labrador
    >>> a.bark()
    Woof Woof!
