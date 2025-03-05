# Problem To Solve

The year is 2001. You’ve been hired to help make the most of the Oakland Athletics baseball team’s dwindling player budget. Each year, teams like the “A’s” hire new baseball players. Unfortunately, you’re low on star players—and on funds. Though, with a bit of SQL and some luck, who says you can’t still create a team that defies expectations?

Given a database called moneyball.db—one that contains information on players, their performances, and their salaries—help the Oakland Athletics find the value in players others might miss.


# Schema

"moneyball.db" represents all of Major League Baseball’s players, teams, salaries, and performances up until 2001. In particular, moneyball.db represents the following entities:

- A player, which includes anyone who’s played Major League Baseball for any amount of time
- A team, which includes all teams, past and present, in Major League Baseball
- A performance, which describes the types of hits a player made for their team in a given year
- A salary, which is the amount of money a team paid one of their players in a given year

# Questions 

1.
You should start by getting a sense for how average player salaries have changed over time. In 1.sql, write a SQL query to find the average player salary by year.

Sort by year in descending order.
Round the salary to two decimal places and call the column “average salary”.

2.
Your general manager (i.e., the person who makes decisions about player contracts) asks you whether the team should trade a current player for Cal Ripken Jr., a star player who’s likely nearing his retirement. In 2.sql, write a SQL query to find Cal Ripken Jr.’s salary history.

Sort by year in descending order.


3.
Your team is going to need a great home run hitter. Ken Griffey Jr., a long-time Silver Slugger and Gold Glove award winner, might be a good prospect. In 3.sql, write a SQL query to find Ken Griffey Jr.’s home run history.

Sort by year in descending order.
Note that there may be two players with the name “Ken Griffey.” This Ken Griffey was born in 1969.
Your query should return a table with two columns, one for year and one for home runs.

4.
You need to make a recommendation about which players the team should consider hiring. With the team’s dwindling budget, the general manager wants to know which players were paid the lowest salaries in 2001. In 4.sql, write a SQL query to find the 50 players paid the least in 2001.

Sort players by salary, lowest to highest.
If two players have the same salary, sort alphabetically by first name and then by last name.
If two players have the same first and last name, sort by player ID.


5.
It’s a bit of a slow day in the office. Though Satchel no longer plays, in 5.sql, write a SQL query to find all teams that Satchel Paige played for.


6.
Which teams might be the biggest competition for the A’s this year? In 6.sql, write a SQL query to return the top 5 teams, sorted by the total number of hits by players in 2001.


7.
You need to make a recommendation about which player (or players) to avoid recruiting. In 7.sql, write a SQL query to find the name of the player who’s been paid the highest salary, of all time, in Major League Baseball.


8.
How much would the A’s need to pay to get the best home run hitter this past season? In 8.sql, write a SQL query to find the 2001 salary of the player who hit the most home runs in 2001.


9.

What salaries are other teams paying? In 9.sql, write a SQL query to find the 5 lowest paying teams (by average salary) in 2001.

10.

The general manager has asked you for a report which details each player’s name, their salary for each year they’ve been playing, and their number of home runs for each year they’ve been playing.

11.

You need a player that can get hits. Who might be the most underrated? In 11.sql, write a SQL query to find the 10 least expensive players per hit in 2001.

12.

Hits are great, but so are RBIs! In 12.sql, write a SQL query to find the players among the 10 least expensive players per hit and among the 10 least expensive players per RBI in 2001
