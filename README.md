# Six Degrees of FIRST

> Source code for http://sixdegrees.uberbots.org/

## Deprecation
Unfortunately, The Blue Alliance has changed moved its database format away from SQL since this was written (many years ago), so it is not feasable to update the data used.  

## About Six Degrees
Six Degrees of FIRST is a tool to find the shortest path between two FIRST teams. Two teams are considered linked together if they have shared an alliance in a past match. Then, the number of links between the two teams are calculated are the final list is output.

Six Degrees of FIRST is based on the websites The Oracle of Bacon and Six Degrees of Wikipedia, which are based upon the the idea of Six Degrees of Seperation, created by Frigyes Karinthy. Six Degrees of FIRST uses a breadth-first search to explore all possible paths, one step at a time, until a shortest one is found. We search our database (derived from The Blue Alliance's) for past alliances to find the shortest path possible between the two teams. Much thanks to The Blue Alliance for use of their match database. 
