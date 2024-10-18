# SOLID Courier System Structure
This is a Spring / RESTful application that demonstrates the potential preliminary structure of a courier service application. The code itself contains many empty functions, simply to serve as a structure to begin with.

## SOLID Principles
Single Responsibility - Each class is responsible for specific actions or functionalities.

Open/Closed - The application is designed and intended to be open for extension but closed for modification once the placeholder logic is properly implemented.

Liskov Substitution - "Objects in the application can be replaced with instances of their subtypes without affecting the correctness of the program." Meaning for example, any service implementation may be replaced with another so long as it adheres to the given service interface.

Interface Segregation - The interfaces are designed to be specific to a particular need.

Dependency Inversion - High-level modules (controller, service) should depend on interfaces, allowing the implemenation to be modified.

## UML Class Diagram
![UML class diagram](/UMLclassDiagramSOLID)
