# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

many forms

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

It means that different classes can either inherit from a superclass or implement interfaces which means that they stick to a certain set of rules and therefore different classes can be treated as the same type of class when interacting with another class.


3. What can we use to implement polymorphism in Java?

interfaces or superclasses

4. How many 'forms' can an object take when using polymorphism?

if it's using an interface than as many as you want.

5. Give an example of when you could use polymorphism.

eg. class of Monitor and Speaker could both implement a IConnect interface which means that a computer class could treat them both as an IConnect class rather than two separate classes.


# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?

When a class has a property that is another class.

7. When would you use composition? Provide a simple example in Java.

Vehicle class could have an engine of type Engine class as one of its properties.

8. What is/are the advantage(s) of using composition?

Allows a class to use behaviour from a group of other classes
makes it possible for the behaviour it's using from other classes to change at runtime

9. When an object is destroyed, what happens to all the objects it is composed of?
They're destroyed.
