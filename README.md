# CS-230-R1977
Design Document and code for The Gaming Room app Draw It or Lose It!

Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?
The Gaming Room developed an Android app called Draw It or Lose It that allows teams to compete to guess what an image is as it slowly renders over a 30-second timeframe.  The company wants to develop a web-based app that serves multiple platforms.  The Gaming Room asked for several specific requirements for the app:
  - Each game have the ability to have one or more teams involved
  - Each team will have multiple players assigned to it.
  - Game and team names must be unique to allow users to check whether a name is in use when choosing a team name.
  - Only one instance of the game can exist in memory at any given time. This can be accomplished by creating unique identifiers for each instance of a game, team, or player.

What did you do particularly well in developing this documentation?  
The Executive Summary and Domain Constrainsts are the strongest pieces of the documentation.  The Executive Summary simple states what we are trying to accomplish for the app to all involved.  The Design Constrainsts section allowed me to sit down and think through what we wanted to accomplish while acknowledging the risks and impacts.  Taking time to weight all options to get the best performance while staying within budget is a balancing act that is important for programmers to consider to best serve clients.

What about the process of working through a design document did you find helpful when developing the code?
Part of designing the app involved meeting the customer's needs in a cost effective way.  Without this perspective, the programming team might come up with solutions that are not in the best interest of the client.  We have multiple patterns, data structures, and algorithms to use to accomplish our goal.  By thinking through the process for both sides allows us to best serve our client with the optimal approach.

If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
I would like to revise and expand on server side development requirements section.  I would give more details about server options from each of the 3 OSs listed as well as discuss cloud options as well.

How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?
The Gaming Room wants to expand their app to multiple  platforms.  Seeing as they were currently running on Android, I determined the best solution would be to develop the app using Windows Azure cloud servers and development kit.  This platform allows for a seamless integration with Android.  More people are familiar with Windows systems and apps which allows the team to quickly develop solutions and bring The Gaming Room team up to speed as well.  Developing through other options like Mac or Linux have a fewer people familiar with the development tools slowing expansion of the app.  Our job is to serve the client's needs.  We do this by listening to them, asking what they want to accomplish, and explaining all their options using a cost-benefit approach.  Without clients, we would not have a job. 

How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?
In class, we completed most of the programming before we began working on the document.  Once I understood all the components of a software design document, I appreciated how taking time to think through a situation--understanding the constraints and goals--allows me to select the best approaches to solve problems and server the client.  We may have 10-12 patterns we can use to solve a particular problem. However, only after understanding what the clients' needs and constraints are can we work to select the best options that are effective, elegant, and cost-effective.
