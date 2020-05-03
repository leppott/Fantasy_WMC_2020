# Fantasy_WMC_2020
Fantasy baseball WMC 2020 league with Stratomatic stats.

With baseball not being played Stratomatic stepped in and is simulating all of the games for the 2020 MLB season.

Our league had the draft and I am using those rosters to display the season stats for each team.

http://www.strat-o-matic.com/2020-season-simulation/

https://fantasy.espn.com/baseball/league?leagueId=2789

# Process
I am downloading the team stats each day at 14:00 Eastern from the Stratomatic website.

In R I scrape the players and stats from HTML to data frames for batters and pitchers.  Then calculate points and save as a combined file.  From there I can slice and dice and create tables and plots.

Everything is in an R Notebook (HTML) with the code and results.  

The table has all of the players for each team and is sorted on total points for the season.

There is a bar chart for current team points broken down by side (batters and pitchers).

And a cumulative total points by team by day.

This is a work in progress and is me just playing around.
