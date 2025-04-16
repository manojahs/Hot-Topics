# Hot-Topics

1)Lazy Loading
------------------
Lazy Loading is a design pattern used to delay the initialization of an object or resource until it is actually needed. This helps improve performance, especially when working with resource-intensive operations or data that may not be required immediately.

Lazy<T> lazyObject = new Lazy<T>(() => new T()); // T is the type of object

Advantages of Lazy Loading:
--------------------------
Improved Performance: Resources are only created when needed, saving time and memory.
Efficiency: Reduces startup time and memory usage when some resources are not required during the program's execution.
Thread-Safety: The Lazy<T> class ensures safe and proper handling of concurrency when multiple threads access the lazy-loaded resource.


Polymorphism 
--------------------

Method overloading basically happens in compile time where it happens in same class where multiple methods having same method name with different parameter and it will get called based on the type of arguments that we pass

method overriding basically happens in atleast 2 different class where method name is both the class will be same and child class will be inheriting from base class and main thing is this is a technique where derived class method will get invoked through base class reference variable during run time 

<img width="661" alt="image" src="https://github.com/user-attachments/assets/69a14f56-d45f-4472-9aa3-55e981229c87" />
<img width="644" alt="image" src="https://github.com/user-attachments/assets/6565a3f1-dc2b-42d7-a12a-c1c4e223b873" />

Sealed class basically used to prevent the inheritance and struct are by default sealed so the struct and class cannot inhertic struct 

<img width="671" alt="image" src="https://github.com/user-attachments/assets/2cdb0017-12bb-49bf-8251-b157c089452f" />

<img width="686" alt="image" src="https://github.com/user-attachments/assets/a5dd67b6-c5b5-46bd-9060-3b3c46359a07" />

<img width="685" alt="image" src="https://github.com/user-attachments/assets/f9d6d4c1-e7f9-4107-90a0-b1ffa99801c5" />

<img width="400" alt="image" src="https://github.com/user-attachments/assets/4b32ac6b-33c8-42d5-b484-0cad9da928cc" />

<img width="655" alt="image" src="https://github.com/user-attachments/assets/5785260d-4531-4803-b540-ea5875179674" />

<img width="675" alt="image" src="https://github.com/user-attachments/assets/b64c465d-fb08-4695-89ab-e5a82e87b4c8" />

<img width="655" alt="image" src="https://github.com/user-attachments/assets/289fc64f-d8e6-4b20-8819-da5645ffb8c6" />



Static Class
------------
A static class is a class that cannot be instantiated and is meant to contain only static members (methods, properties, fields, etc.).
Declared using the static keyword.
All members inside must also be static.
Cannot be instantiated with new.
Often used for utility/helper classes (like Math, File, etc.).
U cann't create extension method for static class but u can create it from instance class of static method


Static Value
-------------
A static value refers to a static field or property inside a class. It's a variable that belongs to the type itself, rather than to instances of the class.
Declared using the static keyword.
Shared across all instances of the class.
Only one copy exists in memory for the whole class.






