# Application Architecture, MVC Design Pattern
01. What are the Pillars of Object Oriented Programming (`OOP`)?
  
  > Abstraction
    Encapsulation
    Inheritance
    Polymorphism

02. How does `export` differ from `export default`?
  
  > Export default only allows for one thing getting exported. So if you are only planning on exporting one thing from a file, use export defualt. Export allows you to export multiple different things.

03. What is Encapsulation?
  
  > Encapsulation is a a topic that refers to wrapping a section of code in a class. This allows it to be shielded from all of the other parts of the code. You can do this by making variables private or public.

04. What are some of the benefits of the `Proxy` object that we are using in our structure for applications?
  
  > Proxies are good for security and making sure that some data is not viewable from outside of the hard code. You can't go into the console and view all of the AppState for example.

05. What the difference between a `class` and an instance of a `class`?
  
  > The instance of a class is usually set in the service of a project. It is also called a Singleton. It is a snapshot of a class set so thatway nothing can change the things inside of it. You can only access the blueprint. A regular class is called in the controller of a project and allows you to change the things inside of it.

06. What is a computed Property?
  
  > Computed properties are a way to grab certain data from inside a file as well as outside of it. It also allows you to set a variable as that data to keep your code concise and easily readable. 

07. What is the purpose of the `MVC` pattern?
  
  > The purpose of the MVC pattern is to give clear definition to where things in your project are happening. It allows you to visualize where things should go and where they are happening.

08. What is the job of the `Controller` in the `MVC` Pattern?
  
  > The Controller's job is to be the middleman between the view and the service. The controller takes inputs from the user interacting with the view and then talks to the service to change data. The controller also updates the DOM.

09. What is the job of the `Service` in `MVC`?
  
  > The Service's job is to change the data stored in the AppState.

10. What is the job of the `Model` in `MVC`?
  
  > The Model's job is to give the blueprint for what something should be and look like. 
