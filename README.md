# wnba_lottery
Tool to provide updated odds by team for the WNBA lottery as teams are revealed

## Description
This repo contains a notebook (`wnba_lottery.ipynb`) that constructs an WNBA Draft Lottery odds tool that can be updated live as the draft order is being revealed. The pre-lottery odds of a team receiving a particular draft position is well-documented, but the odds do not update dynamically as information is learned. With the `Logo` class from the `py_ball` package, a table of updated WNBA Draft Lottery odds can be generated via user input.

## Results
The table below shows the pre-lottery odds for the 2020 WNBA Draft. Each cell contains the percent probability of the team in that row receiving the pick number in the column.

![](lottery_odds.png)
