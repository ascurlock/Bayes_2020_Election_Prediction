# Incumbent Reelection With the “Trump Factor”

Final project for UVA's Fall 2020 Bayesian Machine Learning course.

The Election.ipynb file contains the code for a hierarchical Bayesian regression model based on polling and level of agreement with President Trump. The csv files include the raw data used in the model and the results from sampling, containing the following:

* house_polls.csv: U.S. House polling data from [FiveThirtyEight](https://projects.fivethirtyeight.com/polls/)

* averages.csv: "Trump scores" calculating how often members of Congress agreed with President Trump, also from [FiveThirtyEight](https://projects.fivethirtyeight.com/congress-trump-score/)

* incumbents.csv: 2020 election results for incumbents included in our model, gathered from the [Washington Post](https://www.washingtonpost.com/elections/election-results/)

* presidential_poll_averages_2020.csv: adjusted state-level presidential polling data from [FiveThirtyEight](https://projects.fivethirtyeight.com/polls/)

* Binomial_Candidate_Predictions1.csv: includes the results from sampling using pymc3. This can be used to quickly reproduce the plots on another system.
