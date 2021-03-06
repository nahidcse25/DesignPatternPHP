    Design Patterns:

    Design Pattern: Design pattern is a general repeatable solution to a commonly occurring problem in
    software design.
    
    Types of design pattern:
        1. Creational Pattern
        2. Structural Pattern
        3. Behavioral Pattern
        4. Concurrency Pattern
      
        1.Creational Pattern:
          a. Abstract Factory
          b. Factory
          c. Builder
          d. Lazy Initialization
          e. Singleton
      
        2. Structural Patter:
          a. Adapter
          b. Decorator
          c. Facade:A Facade is meant to decouple a client and a sub-system by embedding many 
              (but sometimes just one) interface, and of course to reduce complexity.
             [Used for reducing coupling]
          
        3.Behavioral Pattern:
          a. Strategy Pattern
      
    Coupling: Coupling means the degree of one module depend on other module.
      	$storage = new Storage();
      	$user->new User($storage);//$user depend on $storage//
      	
    Dependency Injection: Dependency Injection is where components are given through their constructor,method
        or directly into field as a dependency.
      	//storage components gives as constructor to user.
      	
    Dispatch: Dispatch is a process of select a method at run time.
