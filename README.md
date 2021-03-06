# wk_07_d3_Polymorphism-Compostion_Quiz
Repository to hold the files for the Polymorphism &amp; Composition Homework Quiz.

<h1>Polymorphism & Composition Homework - Quiz</h1>
<h2>Polymorphism</h2>

<h3>What does the word 'polymorphism' mean?</h3>

<p>The word polymorphism means that something can take on many forms or shapes.</p> 

<h3>What does it mean when we apply polymorphism to OO design? Give a simple Java example.</h3>

<p>When we apply the concept of polymorphism to OO design in Java we can allow objects of different classes to be manipulated based on the enforced methods require from the implementation of an interface. For example, objects which are instances of classes with varying attributes and methods can be handled with regard to their simularity with the interface acting as a contract that they will have a funtion of a certain name with a set type of return. An object implementing an interface can be manipulated with the methods set by that interface but also "cast" into the class itself allowing methods specific to the object to be called. This increases the flexibility of the program and reduces rigiditiy and fragility.</p>

<h3>What can we use to implement polymorphism in Java?</h3>

<p>We can use Interface in java to implement polymorphism in Java. Super classes can also be used for polymorphism as their child classes can be treated as the parent class or maniupulated handled as the child class.</p>

<h3>How many 'forms' can an object take when using polymorphism?</h3>

<p>The object could take on infinite forms.</p>

<h3>Give an example of when you could use polymorphism.</h3>

<p>Polymorphism could be used when there is a requirement for a collection of objects of different classes to be held in a data structure such as an ArrayList of HashMap.

<h2>Composition</h2>

<h3>What do we mean by 'composition' in reference to object-oriented programming?</h3>

<p>Composition is a methodology for design software programs in which objects are created with a HAS-A relationship to other objects. This moves away from the Inheritance priniciple which uses a IS-A relationship which has the capacity to create issues as a program develops. Composition is a form of futureproofing and increases flexibility.

<h3>When would you use composition? Provide a simple example in Java.</h3>

<p>Composition would be used in any project using a object oriented programming language. In Java if classes shared the same behaviours rather than trying to create a super class with the same methods and overloading with inheritance it would be more useful to create an interface and implement it in the appropriate classes. Therefore an object could have a HAS-A relationship with objects of many classes which implement the same interface.</p>

<h3>What is/are the advantage(s) of using composition?</h3>

<p>Composition helps to make code more robust and future proofs it by reducing hi level dependencies on lo level modules allowing changes to be made without "breaking" the code. This also lends itself to reusing code (Not necessarily true for compostion this is more dependency inversion using interfaces.)</p>

<h3>What happens to the behaviours when the object composed of them is destroyed?</h3>

<p>When an object implementing an Interface is destroyed the interface itself is not changed and the objects calling methods on any other object which are implementing the interface are not affected.</p>
