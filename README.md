# prizepicks-files
**.xlsx Files** - 
The Excel Files are a CFB Rushing and Passing Report that use strictly PFF Play by Play data to filter, join, and sort.
Rushing Chart will show a teams efficency and run frequency in certain gaps, the data is updated in the two tabs with two SQL queries upon the completion of a new game week.
The Passing stats are for QBs and how they preform in different scenarios. Only Week 1 Playing QBs are in right now as I have not needed to look at any teams backup.
These two showcase how I use SQL to create a visualization that can be updated for a new week in minutes and displayed for any team

**Python & CSV File** - 
The python and csv files are a recruiting tool I created to tackle the problem of how good a player is for their size.
A short WR may be faster, but we want to compare them to other short WRs not all WRs including 6'3 players.
This code will use range_h and range_w as variable to set the range of players looked at (by default it will be +/- 1 inch and +/- 10 lbs)
The function will print the players percentiles in their position and built range, as long as the sample size is over 20.
If someone does not have some of the more obscure measurables, you can just hit enter and leave them blank and they will not go on the chart at all.
These charts can be easily sent to give someone a quick breakdown on the physicals of a player
