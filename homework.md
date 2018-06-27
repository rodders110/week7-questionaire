# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

   Polymorphism is a greek word meaning many shapes.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

   Polymorphism in Java means that we can cast objects as multiple types based on inherited properties from a parent class or from interfaces that it implements.
   
   An example could be an Carrot object called carrot that extends a parent class Vegtable and implements an Interface called Iedable

   This object could be a cast as a Carrot, Vegtable or Iedable.

3. What can we use to implement polymorphism in Java?

   We can use Casting to change types of Objects.

4. How many 'forms' can an object take when using polymorphism?

   An object can take an infinite number of forms. It can take one form from its parent class, and a form from any Interface the object impletements and an object and implement multiple interfaces.

5. Give an example of when you could use polymorphism.

   Polymorphism can be used when you wish to call a method that is common amongonst multiple classes in only one method within another class.



# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?

   Composition refers to the way methods are written. 

7. When would you use composition? Provide a simple example in Java.

   When you wanted to write a method that would that would take is Polymorphic rather than writing methods that take in each indiviual object type.

   An example would be writing a method to send data to an output object such as Printer or monitor:

   You could use an interface called Ioutput and implement this in all output objects and then write the method to accept Ioutput objects. 

8. What is/are the advantage(s) of using composition?

   You can write better DRY code.

   You can add similar.

   You can make changes easier including adding or deleting objects without having to refactor code.

9. What happens to the behaviours when the object composed of them is destroyed?

   The behavoirs are also destroyed.
