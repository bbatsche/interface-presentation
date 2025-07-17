# Why Should We Even<br />Use Interfaces?

note: Emphasize 1. Genuine question, want to get response; 2. Not a trick question

***

# Interface Provide<br />Two Key Functions

- Declare reusable pieces of functionality <!-- .element: class="fragment" -->
- Define a class's purpose within an application <!-- .element: class="fragment" -->

***

# What If We Treated Each<br />Function Independently?

- Discrete Functionality Interfaces (DFI) <!-- .element: class="fragment" -->
- Application Role Interfaces (ARI) <!-- .element: class="fragment" -->

***

# Discrete Functionality<br />Interfaces (DFI)

- Encapsulate a snippet of reusable functionality <!-- .element: class="fragment" -->
- Likely applied to many classes across your application <!-- .element: class="fragment" -->
- May be implemented by a trait <!-- .element: class="fragment" -->
- Relatively flat inheritance hierarchy <!-- .element: class="fragment" -->
- Typically an "-able", "-Aware", or "Can-" interface <!-- .element: class="fragment" -->
- Used to declare types for method parameters <!-- .element: class="fragment" -->

***

# Application Role<br />Interfaces (ARI)

- Declare a class purpose within your application <!-- .element: class="fragment" -->
- Will typically be implemented by only a single class <!-- .element: class="fragment" -->
- Inheritance follows whatever practice you prefer <!-- .element: class="fragment" -->
- Used for constructor & property types and with dependency injection <!-- .element: class="fragment" -->
- Underlying functionality not as relevant (trust me!) <!-- .element: class="fragment" -->
