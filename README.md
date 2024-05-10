# Bowling-Scoring-System--


Background  
Bowling is a popular sport all over the world. Over 95 million people bowl in 90 countries spread
across six continents*. Rolling a ball down a bowling lane to knock down the pins at the end of the
lane is how it's played. The situation is diagrammed in Figure 1.  
 

A bowling game consists of ten frames. To knock down all ten pins, the bowler may use up to two
balls in each frame. A strike occurs when the first ball knocks down all of the pins and ends the
frame. A spare is when you knock down all of the pins with the first two balls. A miss is defined as
knocking down fewer than ten pins with the first two balls.
A bowler receives one point for each pin knocked down, as well as bonuses for strikes and spares. A
strike is worth 10 points plus the sum of the next two balls; a spare is worth 10 points plus the next
ball's score. A strike in the tenth frame earns the bowler two extra balls, while a spare earns the
bowler one extra ball. Table 1 shows an example of how a game is scored.
Bowlers use a score sheet that is organised to show the score for each frame and ball. They use an X
to represent a strike and a / (slash) to represent a spare by convention. The following is how the
game in Table 1 would be scored: 

Bowlers used to keep their own scores back in the day. Computers, on the other hand, have enabled
automatic scorekeeping in bowling. Sensors count and tally the number of pins knocked down after
each ball.
 
 

 
Problem 
Design and implement a class that represents an automatic bowling scorer object. It will provide
several methods:  
• a constructor; 
• an int frameNumber method that returns the number of the frame containing the ball about to
be rolled; 
• an int scoreSoFar method that returns the score in the game so far; 
• a boolean gameIsOver method that returns true when the tenth frame has been scored and
false otherwise, and which causes the next roll to start a new game; 
• an int [ ] roll method that, given the number of pins knocked down by a roll of the ball,
returns an array whose length is the number of frames completely scored and whose contents
are the cumulative scores for those frames.  
Table 2 displays the arrays returned by roll in the previously described game. You can assume that
the argument to roll correctly represents the number of pins knocked down by the roll. That is, no
error checking is required. 
