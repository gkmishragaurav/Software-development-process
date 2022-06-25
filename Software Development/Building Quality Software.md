### Building Quality Software

#### Software Coupling and cohesion fundamentals:
- Coupling and cohesion are two fundamental concepts surrounding software architecture. 
- Application architects who maintain a good understanding of coupling and cohesion will find it much easier to design modular, object-oriented software. Furthermore, it will improve their ability to modify and evolve software architectures over time while keeping codebase and integration problems to a minimum.

- Coupling: Coupling is the measure of the degree of interdependence between the modules. A good software will have low coupling. 
- Types of Coupling: 
    - Data Coupling: If the dependency between the modules is based on the fact that they communicate by passing only data, then the modules are said to be data coupled. In data coupling, the components are independent of each other and communicate through data. Module communications don’t contain tramp data. Example-customer billing system.
    - Stamp Coupling: In stamp coupling, the complete data structure is passed from one module to another module. Therefore, it involves tramp data. It may be necessary due to efficiency factors- this choice was made by the insightful designer, not a lazy programmer.
    - Control Coupling: If the modules communicate by passing control information, then they are said to be control coupled. It can be bad if parameters indicate completely different behavior and good if parameters allow factoring and reuse of functionality. Example- sort function that takes comparison function as an argument.
    - External Coupling: In external coupling, the modules depend on other modules, external to the software being developed or to a particular type of hardware. Ex- protocol, external file, device format, etc.
    - Common Coupling: The modules have shared data such as global data structures. The changes in global data mean tracing back to all modules which access that data to evaluate the effect of the change. So it has got disadvantages like difficulty in reusing modules, reduced ability to control data accesses, and reduced maintainability.
    - Content Coupling: In a content coupling, one module can modify the data of another module, or control flow is passed from one module to the other module. This is the worst form of coupling and should be avoided.

- Cohesion: Cohesion is a measure of the degree to which the elements of the module are functionally related. It is the degree to which all elements directed towards performing a single task are contained in the component. Basically, cohesion is the internal glue that keeps the module together. A good software design will have high cohesion. 
- Types of Cohesion: 
    - Functional Cohesion: Every essential element for a single computation is contained in the component. A functional cohesion performs the task and functions. It is an ideal situation.
    - Sequential Cohesion: An element outputs some data that becomes the input for other element, i.e., data flow between the parts. It occurs naturally in functional programming languages.
    - Communicational Cohesion: Two elements operate on the same input data or contribute towards the same output data. Example- update record in the database and send it to the printer.
    - Procedural Cohesion: Elements of procedural cohesion ensure the order of execution. Actions are still weakly connected and unlikely to be reusable. Ex- calculate student GPA, print student record, calculate cumulative GPA, print cumulative GPA.
    - Temporal Cohesion: The elements are related by their timing involved. A module connected with temporal cohesion all the tasks must be executed in the same time span. This cohesion contains the code for initializing all the parts of the system. Lots of different activities occur, all at unit time.
    - Logical Cohesion: The elements are logically related and not functionally. Ex- A component reads inputs from tape, disk, and network. All the code for these functions is in the same component. Operations are related, but the functions are significantly different.
    - Coincidental Cohesion: The elements are not related(unrelated). The elements have no conceptual relationship other than location in source code. It is accidental and the worst form of cohesion. Ex- print next line and reverse the characters of a string in a single component.

- The difference between coupling and cohesion
	- Coupling metrics focus on the number of dependencies between the components of an application. Tightly coupled application architectures contain prohibitively immutable dependency connections. If the applications and services do not require frequent updates and changes, these types of architectures are generally easy to manage. However, tight coupling makes it extremely complex to develop, test, deploy and manage components independently.
	- Cohesion references the degree to which the components of an application share methods and data in common. A cohesive module contains tightly interrelated code, but the fact that components can share common methods and data without knowledge of each other leads to a decrease in direct dependencies. As such, many teams aim to achieve high architecture cohesion and low coupling.

- What are coupling metrics?
	- Tight coupling makes it difficult to alter a single component without causing direct changes to others. Updates, tests and even refactoring are all complicated by tight coupling. A system becomes loosely coupled if individual components require little or no knowledge of the surrounding components to operate. As such, teams can build distributed applications with components that can act and evolve independently. The following formula calculates the level of coupling, C, between components a and b:

	C(a, b) = i + n / (n + 1)

	In this formula, the variable n represents the actual number of direct dependencies that exist between components a and b. The variable i will produce a value that indicates the level of coupling that exists between a and b. Developers can determine i by examining each of those components and identifying the tightest dependency relationship, with 0 representing the lowest level of dependency and 5 representing the highest.
