# CS-230 8-2-Journal-Portfolio-Submission
Submit the completed software design document that you created for your client, The Gaming Room. + README!

- Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?
  - The Gaming Room asked CTS to help turn their Android only game into a cross platform web application. They needed strict control over unique sessions, teams, and players, along with a guarantee that only one game instance could run at a time.
- What did you do particularly well in developing this documentation?
  - The client wanted a web version of their game that enforced unique IDs, allowed team name checks, and supported multiple teams and players. They also needed guidance on cross platform development and how the system would behave in a distributed environment.
- What about the process of working through a design document did you find helpful when developing the code?
  - I clearly defined the domain model and explained how the main classes relate. I also captured the client’s constraints, described the Game Service’s responsibilities, and organized the document cleanly.
- If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
  - The design document gave me a clear blueprint for class structure and system rules. It also clarified data flow and reduced rework by establishing decisions early. I would improve the System Architecture View by adding diagrams and clearer explanations of system tiers and scalability. More detail on concurrency and synchronization would make the document stronger for future developers.
- How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?
  -I enforced a single active game instance, created unique IDs, and built a service layer to validate names and manage objects. Understanding user needs ensured the design aligned with gameplay, business goals, and long term maintainability. 
- How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?
  - My approach used object oriented modeling, rule enforcing services, and clear separation of concerns. In future work, I would add use case modeling, sequence diagrams, prototyping, and design pattern selection to strengthen early design decisions.
