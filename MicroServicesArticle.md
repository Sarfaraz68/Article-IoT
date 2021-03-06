# Microservices
## (In the eyes of a layman)
#### By Sarfaraz Ahmed Khan - (IOT047399)

## Definition
Microservices architecture or simply known as microservices is a collection of services that are loosely coupled and can be managed easily. 

Furthermore, these services can be tested and deployed independently. Microservices architecture is a practice of breaking an application into smaller and independent components which can communicate through an API interface.

## Before The Emergence Of Microservices
In the beginning of software development only highly qualified people could write a computer programme. In 1964 BASIC language was developed which made programme-writing easy for less qualified people. Therefore in the 1960s software began to become lengthy and complex. The computer scientist introduced a modular approach to overcome complexity of the programmes. In 1972 the concept of modularity introduced which led to Modular software development. This concept consists of decomposing large/lengthy code of softwares into loosely coupled and highly cohesive modules that made  sure that one module should focus on single functionality.

After the rise of internet, applications become large and more complex applications therefore  another architecture introduced i.e. Layered Architect which consist of Presentation, Business, Database layers.

## Monolithic Architecture
A monolithic architecture is a unified software program, means composed all in one piece. Monolithic software is designed in which components of the program are interconnected and interdependent. In a tightly-coupled architecture, each component and its associated components must be present in order for code to be executed or compiled.

In 1997 computer scientist/researchers point out the following problems with Monolithic Architecture (MA):

1. Unregulated growth
2. Too many responsibilities
3. Lacks proper Architecture
4. Spaghetti Code
5. Make it working

It was clear that owing to the above mentioned problems Monolithic Architecture was unable to handle the challenges of Modern, Fast-Paced and Web-Scale Software development.

Further we will check out what are the limitations of Monolithic Architecture.

1. Application Scaling: the capacity to make change in size or scale of Applications in (MA) is burdensome and difficult . Monolithic software is developed in a single programming language and therefore it is not possible to implement one single module of it in other programming languages.
2. Development Velocity: adding a new features in monolithic application is difficult because, therefore making changes is slow
3. Release Cycle: at present large release cycles put a company on disadvantage the more large release cycle more chance of losing market. 
4. Modularization: the Modules in Monolithic Architecture are tightly coupled, therefore, as the application begins to grow ,modules begin to merge.
5. Modernization: Modernization of Monolithic application is often expensive and time-consuming.

## Advantages of Microservices
1. Microservices are small therefore easy to build by a team of few developers.
2. Modules are separated that makes development of applications easier.
3. Microservices can be deployed independently. 
4. If there is a bug/error in a service, the entire application will not stop working. After removing the bug/error service can be redeployed.
5. Choosing technology i.e. programming language, database etc,  which suits the requirement of application, in MA is not limited.
6. New features can be deployed and old features can be discarded easily.

## Disadvantages of Microservices
1. Design Complexity: A system which works on many services is bound to be complex. Therefore, Microservice design is complex. A badly designed Microservice is worse than a Monolith.
2. Distributed Systems Complexity:Distributed systems are complex in nature therefore in Distributed Microservices there can be problems such as Overall System latency is higher, Network failure or Individual Node failure and Operational complexities are higher. 
3. Operational Complexity:it is difficult to manage a large number of services.The developer needs to solve the problem, such as network latency and load balancing.
4. Security:  Security of a single software is difficult and security of many services is more difficult.
5. Data Sharing and Data Consistency: Every service has its own database thus making it difficult to share data and keep consistency with other services to run an application.