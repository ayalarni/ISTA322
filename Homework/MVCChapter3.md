#MVC#Chapter3Pages51-66

##Norma I. Ayala-Rosa

1. The book states,Interactions with an MVC application follow a natural cycle of user actions and view
updates, where the view is assumed to be stateless. What does it mean for the view to be stateless?
The server can handle each request uniquely and does not have to keep a session state for the client. It does not keep track of configuration settings, transaction information or any other data for the next session. Any interaction between user and server they don't let you in the machine.

2. The book identifies two kinds of models. Briefly describe each of them.
View model represents data being transferred between views and controllers.
Domain model is the single, authoritative definition of the business data and processes within your application. To manipiulate data or add new process or rule, the domain model is the only part of the application to change.

3. Give an example of separation of concerns from your own life experience. This should be a simple, everyday example.
One type of vehicle for air, water, and land transportation.
Separation of concerns --the domain model and controller logic are decoupled from the user interface.

4. What is a view engine? The component responsible for processing a view in order to generate a response for the browser.

5. The book notes that the three-tier structure, or three layer model, is the most widely used pattern for
business applications. Why do you think that this is true? An answer like, Because it works well,is not a sufficient answer to this question.
It separates the persistence code from the domain model and places it in a new component called the ddata access layer (DAL).
It has no constraints on how UI is implemented and provides good separation of concerns w/o complication.

6. This question requires some outside research. When we study UWP, you will see that the UWP design
pattern is the Model-View-ViewModel (MVVM). What is the difference between MVC and MVVM that makes the worst good for ASP.NET MVC and the second good for UWP?
MVC controllers uses the view. MVVM there is NO controllers. UWP preserves memory.

7. Describe the two parts of the dependency injection (DI) design pattern.
DI or Inversion of Control (IoC) is a design pattern that completes the loose coupling process.  
First part - remove any dependencies on concrete classes from the component.  The constructor no longer cares how the interface is implemented.
Second part - to inject the dependencies declared by the constructor class when instances are created. 

8. Give an example of loose coupling from your own life experience. This should be a simple, everyday example.
Leasing a car -- not thight down to a 72 months payment.

9. What are the two types of testing discussed in the book?
Unit testing - a way to specify and verify the behavior of individual classes in isolation from the rest of the application.
Integration testing - a way to specify and verify the behavior of multiple components working together, up to and including the entire web application.
 
10. What are the seven steps of the test driven development (TDD) work on as stated in the book?
 a. Determine the need to add a new feature or method to the application. (write test)
 b. Write the test that will validate the behavior of the new feature when it is written. (Run test and fails)
 c. Run the test and get a red light. (Run and passes)
 d. Write the code that implements a new feature. (Refactor once)
 e. Run the test again and correct the code until you get a green light. 
 f. Refactor the code if required. i. e. reorganize statements, rename the variables,...
 g. Run the test to confirm that your changes have not changed the behavior of your additions.