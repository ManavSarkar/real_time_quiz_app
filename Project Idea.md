# Project Idea
## Brief
We know a lot of quiz apps and most of them are either offline, and even if online, we donot experience any competition or match between friends. Hence a real time quiz app is what we can make. The idea is we have a quiz app where some users can compete against each other(consider group of 5 or 10 it can be decided though) and each question will have a certain time limit to answer. At the end of quiz questions(may be 5 or 10) we will show the results.

## Results
The results will include the following things
- Leaderboard.
- Rank of user
- Time taken
- Out of scope - Points

## Quiz Type
- The quiz will be played in different categories and the user will be able to play on different categories.
- Each quiz type will have different competition
- Any category having more than the threshold player count will be added to new competition.
- On completion of quiz, they will be redirected to quiz.


## What is being implemented?
Well this a brand new idea and hence the project needs to be implemented from scratch. Any internet resource usage is welcomed. 

## Implementation

### Frontend

 - Using Flutter framework and open source plugins, the frontend should be implemented.
 - The quiz questions data need not to be implemented. Use any free API like opentdb and many more. 
 - Authentication is out of scope for now. Save the data locally. On connection, send the data to backend and it will handle the rest.

### Backend
- Use socket for real time communication.
- Follow the docs https://socket.io/
- Rest is required to be implemented.

