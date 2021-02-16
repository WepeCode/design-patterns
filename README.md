#### Design Patterns Explained 

Design patterns serve as a blueprint to problems that have long been solved by developers. Think of them as being reusable template solutions, irrespective of the programming language, design patterns are aimed at giving us a generic solution which can be then converted to a code solution. 
Design Patterns are classified into three categories namely Structural, Behavioural and Creational. So it wont be entirely surprising if a solution we write contains different patterns, this is move evident in big enterprise projects, where you find that a project consists of a Memento for storing objects locally, a strategy for controlling similar flows like Facebook and Google registration, even a delegate where an object asks another to perform a task on its behalf. Design patterns can also help with code readability, it’s easy to read code that follows a certain structure, since you can easily see each individual components of the entire system. If a new developer is joining your team it won’t take them long to see that your’e using an MVVM pattern without even asking anyone, they can immediately find a login controller. This can also serve an a documentation to how they should add a new feature. Design patterns help us model relationships between related and unrelated objects, this relates strongly to behavioural patterns because they’re more concerned with object interaction. 

Code structure is clearly defined when using design patterns, even before openning a header file to see methods definitions. By a mere look at the folder structure you will see if a design pattern is present. MVC, MVVM, VIPER and VIP are good examples of structural patterns.  

We’re living in a rapidly changing world, most companies start with a small application which may rapidly change to have more features, this change can be a cost to business especially if scaling becomes a problems due to a bad design. What this usually means is new and old developers will start finding it hard to make simple changes as the application grows, this may be due to code that’s hard to read, meaning that developers spend hours trying to add and fix things. All these problems a more prone to applications that are not properly designed. Design patterns allow us to identify and group problems into categories, and apply reusable solution templates to these problems. Essentially our code becomes easy to scale when we can clearly identify each parts of it and how everything relates to each other. 

#### Structural Design Patterns. 
Structural patterns are concerned with how classes and objects are composed to form larger structures. Structural class patterns use inheritance to compose interfaces or implementations. As a simple example, consider how multiple inheritance mixes two or more classes into one. The result is a class that combines the properties of its parent classes. This pattern is particularly useful for making independently developed class libraries work together

  1. Adapter Pattern, adapts' one interface for a class into one that a client expects
  2. Aggregate Pattern, a version of the Composite pattern with methods for aggregation of children
  3. Composite Pattern, a tree structure of objects where every object has the same interface
  4. Decorator Pattern, add additional functionality to an object at runtime where subclassing would result in an exponential rise of new classes
  5. Facade, create a simplified interface of an existing interface to ease usage for common tasks
  6. Flyweight Pattern, a large quantity of objects share a common properties object to save space
  7. MVVM, facilitates a separation of development of the graphical user interface with the help of mark-up language or GUI code. The full form of MVVM is Model–View–ViewModel.
  8. MVC, used to decouple user-interface (view), data (model), and application logic (controller). This pattern helps to achieve separation of concerns

#### Behavioural Design Patterns. 
Behavioural patterns are concerned with algorithms and the assignment of responsibilities between objects. Behavioural patterns describe not just patterns of objects or classes but also the patterns of communication between them. These patterns characterise complex control flow that's difficult to follow at run-time. They shift your focus away from flow of control to let you concentrate just on the way objects are interconnected.

a) Command pattern, Command objects encapsulate an action and its parameters
b) Iterator pattern, Iterators are used to access the elements of an aggregate object sequentially without exposing its underlying representation
c) Mediator pattern, Provides a unified interface to a set of interfaces in a subsystem
d) Memento Provides the ability to restore an object to its previous state (rollback)
e) Observer pattern, a.k.a. Publish/Subscribe or Event Listener. Objects register to observe an event that may be raised by another object
f) State pattern, A clean way for an object to partially change its type at runtime
g) Strategy pattern, Algorithms can be selected on the fly, using composition

#### Creational Design Patterns. 
Creational design patterns deal with object creation. They solve a problem of a client knowing how objects are created. They are based on the idea of encapsulating information about the concrete types an object uses and hiding implementation details of how objects are created  

Examples. 
 a) Abstract Factory, which provides an interface for creating related or dependent objects without specifying the objects' concrete classes.
 b) Builder, which separates the construction of a complex object from its representation so that the same construction process can create different representations.
 c) Factory method, which allows a class to defer instantiation to subclasses.
 d) Prototype pattern, which specifies the kind of object to create using a prototypical instance, and creates new objects by cloning this prototype.
 e) Singleton, which ensures that a class only has one instance, and provides a global point of access to it.

There’s no doubt investing time into learning these carries enormous benefits. It will definitely take time for one to get used to the habit of studying design patterns but practice makes perfect. We will start by discussing creational patterns in the sections to follow.
