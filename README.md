# C
Snippets of Code written in C#.
This is a collection of code samples and projects written in C#.

Definitions and Items created in snippets:
Class - gathering information into a meaning way to create an entity- Example - cars, trucks, suvs . The entire picture of a group which can use lots of memory so instances are used

Object - is a class in the system namespace

Instance - these are methods that belong to a class. These can be used to compare cars and trucks and the gas mileage difference between the two for example.

Virtual Method - this is a method that you build because you want to be able to override it with another method,class, or variable. Public virtual string ToString() for example 

Static Method - this is a class that can only contain static members. This is a placeholder for static methods or fields. Never change


Generic - is a way to remove casting, line up types, and reduce boxing. They are used to accept a type. Example class car<T>  . You can also use to have statements like this one - if returns a boolean expression
if (value==1)
{console.writeline(“One”)
else 
console.writeline(“Not One”);
}
//ternary is identical to this following shorthand
console.writeline(value==1 ? “One”: “Not One”);


Inheritance - for our class car we can inherit from class automobile and grab functionality that class  has already built.  Variables such as wheels, engine, fuel etc if already built can then be used again in class by adding in the inheritance. class car : automobile

Multiple Inheritance -  You can only inherit directly from one base class using C# but you can create a switch statement or use abstract classes with multiple interfaces.

Interface - no code or data -  this is a tool to separate the names and signatures of the methods of a class from the method’s implementation. You cannot define any fields in the interface for example (not even static ones).

Abstract Class - Abstract classes are would be used when when you need a class used in inheritance and polymorphism, but you don’t need to instantiate (or make it an object),you really only need to make it a subclasses. They are used when you want to create a group of subclasses that share some common implementation code, but you also want to make sure that the objects of the superclass cannot be created. 

Override - can be used when parent class is virtual.  Definition from MSDN - The override modifier is required to extend or modify the abstract or virtual implementation of an inherited method, property, indexer, or event.

Overload - used when you need to use the same functions on a different type or group. Parameters change  which you separate with commas but the return type needs to be the same type. You can’t change it. 

Polymorphism- like virtual methods you can use the same statement and call a different method so you can have a class car and a class truck that all inherit from automobile and be set as public override string GetTypeName(). Automobile can be set to public virtual string which returns “I am an automobile”.  The car and truck with return “I am a car” or  “I am a truck” while In the same hierarchy the suv class if you do not use the getTypeName method will return “I am an automobile” 




