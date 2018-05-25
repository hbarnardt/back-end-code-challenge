# Back End Development Challenge

## Overview
You'll be building a terminal based multiplayer game of up to 4 players. The game consists of presenting multiplication challenges to each participant, the first person to answer the sum correctly wins the round.

## Design and behaviour

- The cli should be able to run in either server or client mode. In server mode, the application should run both server and client connecting to the local server.
- The total number of rounds and round max time (The max time a user to the multiplication challenge) should be configurable when starting the server. 
- The server should accomodate for players connection latencies.
- A player wins a round by getting the multiplication challenge correct and be the quickest answering.
- At the end of each round, a scoreboard for the round should be shown with player response and player statistics such as response times per round, total average response time, standard deviation of response time. 
- At the end of the game a scoreboard should be shown with full game stats as depicated above. 

The design of the communication protocol is up to you. A reasonable scoring system is up to you, the last person to answer (or timeout due to max round time) should be given 0.  

### Remarks 

Treat this as a production ready application. Update the readme to include steps on how to build, run and test the app. 

You are encouraged to include some notes about the aspects you didn't get time to complete and how you would plan to further develop/improve the application given more time. Please include them in this readme rather than in an email so that others can see them when we share your work internally.

What we are looking for in your submission:

- Good design decisions
- Creativity
- Code readability
- Modularity 

### Restrictions
- You may use any language to write this code.

### Bonus Marks
- Using golang
- Unit tests

### Submission 
The results have to be shared as a git repository.

You can either create a private repository on your favourite git hosting provider and then give access to:

- seline (AT) hearxgroup (DOT) com
- thomas (AT) hearxgroup (DOT) com

Or create a public repository and send the link to both of these email addresses

Or send the whole repository, zipped (including the .git directory) to both of these email addresses

Please only submit your work when it is completely done!
