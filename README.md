# March-Madness-Data-Visualization-Project

This project aims to predict March Madness game upsets. Predicting an upset involves and considers many factors and unknowns (team performance in the 5 games prior to the tournament, player lineups, offensive/defensive metrics, team efficiency, etc.) from team to team.

This project will:

1. Take all factors, unknowns, and confounding variables into account.
2. Contain multiple machine learning models and metrics to measure team performance.
3. Work with multiple data sources (Bart Torvik, Official NCAA datasets, Kaggle, etc.) to ensure overall accuracy and analysis.

An upset is defined by the NCAA as a lower seeded team beating a higher seeded team when there is a seed difference of at least 5. For example, a 12-seed beating a 5-seed would be an upset due to the seed difference of 7. 
Mathematically, this can be labeled as a binomial probability distribution where let X = a 5 seed difference team winning (P = 1), and let Y = a 5 seed team losing (P = 0) (high-level overview/explanation).

The data will be pulled, cleaned and analyzed before we run multiple machine learning models as mentioned above. I will analyze all of the results to see which kind of model gives the most accurate and complete picture of our data. I will provide graphs for each model to add a visual component.

Core Research Question: Can we predict upsets in March Madness?

Questions that could help answer this:

Do teams' performances in the 5 games immediately before the tournament predict upsets (e.g., hot/cold streaks)?
Do trends exist among past upsets that can be used to predict upsets in future seasons? – Which team performance metrics (from Bart Torvik) most strongly predict upsets in the NCAA tournament?



