# Class Methods as Alternative Constructors
In object-oriented programming term "constructor" refers to special type of method that is 
automatically executed when an object is created from a class. The purpose of a constructor is to intialize
the object's attribute, allowing the object to be fully functional and ready to use.

However, there are times when you may wan to create an object in a different way, or with differernt intial values, than what is provided by the default constructor. Thi s
is where class methods can be used as alternative constructors.

A class method belongs to the class rather than to an instance of the class. One common use case for class methods as alternative constructors is when you want to creae an object from data that is stored in a different fromat, such as a string or a dictionary. For example, consider a class named "Person" that has two attributes: "name" and "age". The default constructor for the class might look like this:

    class Person:
        def __init__(self, name, age):
            self.name = name
            self.age = age

            

