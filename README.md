# Draft Prediction

## Overview

Taking information from the top 200 players that enter the combine we will cross refrence this with high school recruiting and college career stats to predict both what pick or what round they would be picked in.


## The Data

Data was taken from Stathead.com for the combine.  This was limited to 200 players by the website out of the around 300 invited every year.

Data for collge season stats and high school ratings were gathered by college football data api

Combine stats span from 2001 to 2015

Season stats span from 1997 to 2015

High school recruiting spans from 2000 to 2015 because the api only goes back to 2000


## EDA

Our data was skewed to more recent players since high school recruiting data was not as available from the api.

Most limiting data group was the combnine data that was held to just 3000 to begin with.

After all data was combined and refined we were left with just 936 players to build our model off of.


## Modeling

I modeled two different sets of data. One included dummied school and position data and the other one did not to see if these would really play into accuracy of draft position.

With those two sets of data i proceeded to do linear regression to test for draft number overall and random forest for the multiclass of which round. Both were refined.


## Conclusion

There is some promise to d=predicting based on combine as these are usually the top players in college.

More data is needed since this did leave out defense stats for everything except interceptions.





## Next Step

Raise money to pay for the 500 dollars to obtain accurate historical college stats data.

Remove combine restriction to include all 256 players that are drafted every year.

Predict against AV which is approximate value that is how much impact a player has made at their position in the NFL ( of course Tom brady has the highest) 

Analyze impact of team needs and how they affect the early rounds.
