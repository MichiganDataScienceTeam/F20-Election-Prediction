# election-prediction

### Predicting the 2020 Presidential General Election


The general election is coming up in November, and prediction models based on polls and other factors have become a popular way of keeping track of its trajectory: see [FiveThirtyEight](https://projects.fivethirtyeight.com/2020-election-forecast/), The [Economist](https://projects.economist.com/us-2020-forecast/president), and more.


## The Task:

Starting with [this base model](https://colab.research.google.com/drive/1iFcc44FMrKm4r_p83l2zVDxLLkh9K8KZ?usp=sharing) which operates on just polling data, build your own election model.

1. Who can predict the election results most closely?
2. What can the model output tell us about election dynamics?


## The Data:

You can use any data you're interested in (besides, of course, output from other prediction models.) Some places to get you started:
- The Economist's [polling data](https://docs.google.com/spreadsheets/d/e/2PACX-1vQ56fySJKLL18Lipu1_i3ID9JE06voJEz2EXm6JW4Vh11zmndyTwejMavuNntzIWLY0RyhA1UsVEen0/pub?gid=0&single=true&output=csv)
- Polling data (current and historical) from [FiveThirtyEight](https://github.com/fivethirtyeight/data/tree/master/polls)
- [Economic indicators](https://github.com/fivethirtyeight/data/tree/master/election-forecasts-2020) used in the FiveThirtyEight model

## Resources:

- [Writeup](https://projects.economist.com/us-2020-forecast/president/how-this-works) of The Economist’s model.
- [Writeup](https://fivethirtyeight.com/features/how-fivethirtyeights-2020-presidential-forecast-works-and-whats-different-because-of-covid-19/) of 538’s model
- [Paper](http://researchdmr.com/HummelRothschild_FundamentalModel.pdf) on fundamentals models 

## Miscellaneous:

Some ideas to get you started:
- As the base model page mentions, incorporating house effects and mode effects might remove some bias.
- Incorporate more types of data: economic indicators, Twitter sentiment (?), etc
- Incorporate information about how covid might affect turnout
- Incorporate how vote by mail loss rates affect turnout given reported likelihood of different voters voting by mail
- Incorporating geographic and demographic similarities into poll interpolation
- Weighting polls by 538 grade of polster
