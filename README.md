# Draw-it-or-Lose-it-Software-Design

Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?

The client for the project was The Gaming Room. It's a company that wanted to expand their existing Android game called "Draw It or Lose It" into a web based multi-platform application. Their main goal was to make the game accessible across different operating systems and devices while supporting multiple games running at the same time. The software needed to manage games, teams, and players reliably, enforce unique names to avoid confusion, and remain scalable so the system could grow over time. My task was to design a backend focused solution that could support real time gameplay while remaining platform independent and easy to maintain.

What I Did Well in Developing the Documentation

I did particularly well with organizing the system using object-oriented principles and explained those decisions in the documentation. The use of a base Entity class with shared properties along with clearly defined relationships between games, teams, and players helped keep the design clean and logical. I also did some strong job evaluating operating platforms and tying those evaluations directly back to the client’s requirements. Instead of just listing pros and cons, I focused on how each platform would actually impact deployment, scalability for the specific application.

What about the process of working through a design document did you find helpful when developing the code?

Working with the design document before writing code made the development process much smoother. By defining class relationships, constraints, and system behavior up front I didn’t have to make major structural decisions while coding. The design document acted like a roadmap especially when implementing patterns like the Singleton for the GameService. Having those decisions already justified and documented helped reduce uncertainty and prevented rework later. It also forced me to think about edge cases like duplicate names and concurrent access, earlier than I normally would have.

If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

If I could revise one part I'd expand the system architecture view section. It wasn’t strictly required for this project but adding a simple architectural diagram showing client-server communication and data storage would improve clarity. It would make the design easier for nontechnical stakeholders to understand and would better prepare the document for real-world use beyond an academic setting.

How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?

I interpreted the user’s needs by focusing on simplicity and accessibility. Players shouldn't have to worry about duplicate game names, platform limitations, or losing game state if they switch devices. Those needs drove decisions like centralizing game management with a Singleton service and keeping all core logic on the server side. This is critical because good software design is not just about making something work — it’s about making it intuitive and reliable for real people. Ignoring user needs often leads to technically functional systems that are frustrating or inefficient to use.

How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

My approach  starts with understanding the problem domain and breaking it down into manageable components. I focus on defining responsibilities early using object-oriented principles and identifying constraints that will affect scalability or maintenance. In the future I would continue using techniques like UML modeling, requirement tracing, and design patterns, but I would also incorporate more user-focused analysis such as user stories. It would help ensure that technical decisions stay aligned with real-world use cases and business goals.
