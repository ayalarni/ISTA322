#MVC#Chapter4Pages67-94

##Norma I. Ayala-Rosa

1. Using automatic properties is a shortcut that avoids several explicit steps. List the steps that the use
of automatic properties avoids.
Create the pattern of a field-backed property, without defining the field or specifying the code in the getter and setter.
It saves typing, create code easier to read, but preserving the flexibility that a property provides.

2. Using the object initializer syntax is a shortcut that avoids several explicit steps. List the steps that
the use of object initializers avoids.
It allows to create and populate the Product instance in a single step.
The braces ({}) after the call to the Product name form the initializer, which supplies values to the parameters as part of the construction process.  It allows to initialize the contents of collections and arrays as part of the construction process.

3. What is the purpose of creating extension methods? They are a convenient way of adding methods to classes that you do not own and cannot modify directly.

4. What is the one feature of extension methods that will always allow you to identify a method as an extension method?
Extend the functionality of a class by using an extension method, by using only the class members that you had access to.

5. How do you create an extension method that filters the results returned by the method on a user specified criterion?
Use yield keyword.

6. Explain the syntax of a lambda expression. The term "lambda expression" originates in the lambda
calculus developed by the mathematician Alonzo Church in the 1930's. There is a class of programming
languages that are based on the fundamental ideas of lambda calculus.
Is a conscise format for expressing a method body in a delegate.
It is an anonymous function.

7. This will require some outside research. What is the distinction between an anonymously typed variable
and a dynamically typed variable? It has no name but it has a type.

8. You are having a discussion about C# with a friend of yours that uses another language. You are
tellig him about C#'s LINQ library. How would you describe to him the difference between LINQ's
SQL-like notation and LINQ's dot notation?

9. What exactly does the await keyword do? to treat the result from the GetAsync method as though it were a regular
method and just assign the HttpResponseMessage object that it returns to a variable.

10. What is the connection between await and the async keywords? they are implemented using some clever compiler tricks, meaning that they allow a more natural syntax, but not change what is happening in the methods to which they are applied.