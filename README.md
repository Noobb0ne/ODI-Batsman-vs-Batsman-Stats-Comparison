# ODI-Batsman-vs-Batsman-Stats-Comparison
In this we have a list of 35 batsmen, we can enter their names get each players stats and compare them.
We take five parameters for this comparison in a specified time frame different for each player:

Runs Per Innings or RPI - Total Runs Scored / Total Number of Innings Played
Strike Rate or SR - (Total Runs Scored / Total Balls Faced) x 100
100s Scored - Count of centuries scored
50s Scored - Count of half-centuries scored
Team Contribution - (Total Runs Scored by player / Total Runs Scored By Batsmen) x 100.

The two batsmen we compare can be from different eras, so we normalize the stats for the selected player as:
Runs Per Innings - We will take the ratio of total runs scored by batsman 1 / batsman w by total runs without batsman 1/ batsman 2
Strike Rate - We use the same logic as RPI. What we do is we calculate the SR with batsman 1 / batsman2 by SR without batsman 1 / batsman 2
100s Scored - We take the ratio of total number of innings  batsman 1 / batsman2 played by centuries scored by  batsman 1 / batsman2
50s Scored - We take the ratio of total number of innings  batsman 1 / batsman2 played by half-centuries scored by  batsman 1 / batsman2
batsman 1 / batsman 2 is the stats of batsman 1 are displayed first then the stats of batsman 2 are displayed.
