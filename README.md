# Baseball
This code simulates baseball games.

This does not include all of the code necessary to simulate games and evaluate performance, but it should provide enough to demonstrate the general idea. I'd be happy to provide further information upon request.

A02. MLB API 
This code extracts data from a web API and cleans it. 
It also creates a variety of new variables, including stats calculated on a rolling basis.

A03. Steamer
This automates downloading projections from the internet.
It also creates a variety of new variables.
These projections are generally used to impute model inputs when limited data are available.

A04. Bullpen
This scrapes data from the internet.
It also creates a variety of new variables.

A05. Rosters
This code extracts data from a web API and cleans it. 

B01. Matchups
This creates matchup files my merging together datasets.
These files can be used as inputs in the Monte Carlo simulation.

B02. Simulations
This simulates baseball games and returns information about scores and player performances.

M01. Impute Inputs
This standardizes statistics.
It also uses projections from the Steamer website to impute model inputs when limited data are available.

M02. Predict PAs
This uses logistic regressions and neural networks to predict the outcome of plate appearances (batter vs. pitcher matchups).

M03. Predict Pulls
This uses logistic regressions to predict when pitchers will be removed from a baseball game by their managers.
 