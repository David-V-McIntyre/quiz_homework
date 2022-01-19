# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

Answer: The ability for something to change shape.


2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

Answer: It means that an instance of a class can be treated like another class. For example you could have a ISpeaker interface with a makeSound() method - this could then be implemented by other objects such as Headphones or CinemaSpeaker (where the Headphones “play music” and the CinemaSpeaker “plays movie sounds” etc)

3. What can we use to implement polymorphism in Java?

Answer: We use an interface, abstraction or inheritance.

4. How many 'forms' can an object take when using polymorphism?

Answer: I don’t know if I fully understand this question. I guess  an ISpeaker could potentially be an infinite number of different objects as different objects could implement it. 

EDIT: As many as it needs.

5. Give an example of when you could use polymorphism.

Answer: You could use polymorphism whenever multiple objects will need to utilise the same method with different outcomes. For example if you create an “IAnimal” interface you could create a “move” method. The other classes would then implement this method in different ways - for example a Horse child class would use “move” to “trot” or a Fish would use “move” to “swim”



# Composition and Aggregation

6. What do we mean by 'composition' in reference to object-oriented programming?

Answer: It is when an object is composed of other objects.

7. When would you use composition? Provide a simple example in Java.

Answer: A house object would contain a door object, a floor object and wall objects for example.

8. Give a difference between composition and aggregation?

Answer: In composition the object is created inside of another object, in aggregation the objects are created outside and passed into the other object.

9. What is/are the advantage(s) of using composition/aggregation?

Answer: Composition allows you to free up memory by destroying unused objects when the parent object is destroyed. 

Aggregation allows you to re-use code.

10. When using composition, when an object is destroyed, what happens to all the objects it is composed of?

Answer: the internal objects are destroyed as well.

11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?

Answer: The external objects continue to exist.