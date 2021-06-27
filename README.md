# CS-230
SNHU CS-230 Operating Platforms 2021
27 June 2021

* Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?
  Draw It or Lose It is a game application for The Gaming Room. They required help creating their spinoff version of a game show Win, Lose or Draw, where players try 
  and guess what an image is before it fully renders. The client wanted help setting up a web based software that they could use for their game. They had several needs 
  to achieve this goal: the game needed to be multiplayer (online accessable), code ensuring that there was only one instance of each player, team, and game running at 
  a time to save resources, and server/OS recommendations fit to their specific needs.
  
* What did you do particularly well in developing this documentation?
  I felt that my summaries and descriptions of the clients problems went well. There are many important needs of the client for creating and running their software to 
  their and our standards. I felt that my summaries were well thought out, and consice to the client's needs.
  
* What about the process of working through a design document did you find helpful when developing the code?
  The importance of code like singletons was very helpful in developing this project. Ensuring that the code would not create multiple versions of itself helps save 
  system space, and limits errors of code referring to one of many instances of a similar object. Not doing this can easily lead to issues such as memory leak, where 
  the system runs out of memory because of discarded but not deleted instances and variables. It also avoids changes to variables not going to the relevant one, leading 
  to data being lost.

* If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
  The section with evaluation, domain model etc. could probably benifit from going over the section again and fleshing out more as I learned more in the class. As it 
  was written half way through the class, there is much more I could add if it were a real version of the document. The system architecture section could also have some 
  content written under it, but it was not required for this class.

* How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?
  The user is who you are designing the software for, so it is necessary to make what they want you to. They are also in charge of funding and creativity behind the 
  project, it is literally our job to follow their needs as much as humanly and hardware allow us to. Interpreting their needs involves getting as much detail as you can
  from them about their project, and turning those into goals for the design. What do they need and how can you accomplish that effeciently and safely with coding in mind.
  Some clients may have unrealistic expectations, and should be notified of such and offered alternatives.

* How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application? 
  In designing the software, since in this senario I am a junior developer, I had help and pointers with some of the code already created. Filling in the blanks was fairly
  easy, and searching around online in resources like stack exchange helped guide me when I couldn't figure something out. In other software designs, getting help will 
  still be a good strategy. Asking coworkers or searching around online can help eliminate struggles and write good code.
