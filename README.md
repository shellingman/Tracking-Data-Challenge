# Tracking-Data-Challenge
Data science challenge for soccer tracking data.

Discription of the task:

Events describe passes from open play in the same general area of the field. The player locations data is a record for the locations of the players and the ball for each of these passing events. These events can be joined together in both locations using the GameEventID field. The passing player is denoted by the IsEPlayer in the player locations data, and EPlayerID in the event data. Whether or not these individual possessions resulted in a goal is given by the IsPossGoal field. Note that the orientation of the coordinates is always going from left to right (negative to positive towards the opposition goal).

 
We would like you to demonstrate your skillset by using the player locations data to make insights about the probability of individual passes resulting in goals (denoted by the IsPossGoal field). We are looking for constructed aggregate measures (players in front of the passer, opponents in proximity to ball, etc..) of the player locations data that might be useful in predicting the previously stated IsPossGoal response. You do not necessarily have to make predictions on the IsPossGoal field, rather we are looking for constructed measurements of the on-field situation that might be used for such, as well as their general specific signifigance.
