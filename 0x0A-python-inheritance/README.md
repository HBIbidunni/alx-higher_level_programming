# ALX Project: Python - Inheritance.

* In this project, the emphasis is on <b>inheritance</b>, <b>multiple inheritance</b> and their purpose.
* <b>Inheritance</b> is a core concept in <b>Object-Oriented Programming (OOP) languages</b>.
* It is a mechanism  that allows you to create a hierarchy of classes that share a set of properties and methods by deriving a class from another class.
* All cases of <b>multiple inheritance</b> exhibit one or more <b>dynamic ordering</b> or <b>diamond relationships</b> (where at least one of the parent classes can be accessed through multiple paths from the bottommost class).
* Some built-in functions it uses are: `isinstance`, `issubclass`, `type` and `super` built-in functions.

> For instance: using the built-in functions above, the lines below prints <b>1</b> 
                    
                    class Base():
                        """ My base class """

                        __nb_instances = 0

                        def __init__(self):
                            Base.__nb_instances += 1
                            self.id = Base.__nb_instances

                    class User(Base):
                        """ My User class """

                        def __init__(self):
                            self.id = 89
                            super().__init__()

                    u = User()
                    print(u.id)

> All feedbacks, comments and suggestions on my codes are most welcome. Kindly take a look.
