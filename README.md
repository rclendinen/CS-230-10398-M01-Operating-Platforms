# CS-230-10398-M01-Operating-Platforms

Software Design Reflection – Draw It or Lose It

Client and Software Requirements Summary

The client for this project was The Gaming Room, a company seeking to evolve its Android-only game, Draw It or Lose It, into a web-based, multi-platform application. The client required a distributed solution capable of supporting multiple concurrent game sessions, each containing multiple teams and players, while strictly enforcing unique game and team names. From a technical perspective, the software needed to be scalable, platform-independent, and capable of maintaining consistent server-side game state across multiple client connections.

Strengths in Documentation Development

One area I performed particularly well was clearly mapping business requirements to technical design decisions. I effectively documented how object-oriented principles such as inheritance, encapsulation, and controlled access to shared resources informed the system’s design. The use of a singleton service layer to manage game instances and unique identifier generation was clearly justified and aligned with the client’s concurrency and scalability requirements. Additionally, the documentation was written in a way that balances technical accuracy with readability, making it accessible to both technical and non-technical stakeholders.

Value of the Design Document Process

Working through the design document forced me to think critically about architecture and data flow before writing any code. By defining the domain model, relationships between entities, and responsibility boundaries early, I reduced ambiguity during implementation. This process helped prevent issues such as duplicate logic, unclear ownership of data, and poorly defined interfaces. As a result, the coding phase was more efficient, structured, and aligned with the original design goals.

Area for Revision and Improvement

If I could revise one part of the documentation, I would enhance the System Architecture View by including architectural diagrams and more explicit descriptions of client–server communication. Adding visual representations of service boundaries, data flow, and request handling would improve clarity and make the design easier to evaluate from a systems engineering perspective. This improvement would also strengthen communication with business leaders and future developers.

Interpreting and Implementing User Needs

I interpreted user needs by focusing on reliability, fairness, and usability within a multi-user environment. Users need assurance that game sessions remain isolated, that names are unique, and that gameplay behaves predictably regardless of how many users are connected. These needs were addressed by implementing centralized server-side control of game state, enforcing uniqueness constraints before entity creation, and maintaining a single source of truth through the service layer. Considering user needs is critical because technical correctness alone does not guarantee a successful application—usability and trust are equally important for adoption and long-term engagement.

Software Design Approach and Future Strategy

I approached software design by decomposing the system into logical components and applying object-oriented design principles and established design patterns. I focused on separation of concerns, scalability, and maintainability while ensuring that the design could evolve as requirements change. In future projects, I would continue using techniques such as UML modeling, architectural pattern evaluation, iterative design reviews, and early constraint analysis. These strategies help reduce risk, improve code quality, and ensure alignment between technical implementation and business objectives.
