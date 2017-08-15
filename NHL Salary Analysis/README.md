# NHL Salary Analysis

1. I ran a scraper for the CapFriendly and made a data set that contains salary and various statistics including team, opponents and players.

2. I ran lasso regression to see which variables are important to predict salary.
The following are the important variables among all the variables.

['AGE', 'year', 'GP', 'GF', 'Opp GA60', 'SF', 'Sh%', 'TM Sv%', 'Sv% Rel', 'Opp Sh%',

'CA60 RelTM', 'TM CSh%', 'Opp CSh%', 'Opp CSv%', '%ofTeam OZFO', '%ofTeam DZFO', '%ofTeam NZFO', 'FirstA', 'Pts', 'Pri. Pts', 'iCorsi', 'NZFO']

3. I ran deep learning model based on these important variables. I am able to predict salary with an error rate of about 1.0 million.

