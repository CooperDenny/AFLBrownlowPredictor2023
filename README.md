# AFLBrownlowPredictor
This repository contains an R Markdown document and associated files for leveraging an ordinal logistic regression model to predict the 2023 Brownlow Medal votes awarded to players in each AFL game, based on game statistics and other metrics.

## Predicted Leaderboard

The model predicts the following top 20 for the 2023 Brownlow Medal. Predicted votes are pretty close to the actual votes.

| Player | Team | Predicted Votes | Actual Votes |
| :----- | :--- | :-------------- | :----------- |
| Nick Daicos | Collingwood | 31 | 28 |
| Marcus Bontempelli | Western Bulldogs | 30 | 29 |
| Lachie Neale | Brisbane Lions | 28 | 31 |
| Christian Petracca | Melbourne | 28 | 26 |
| Zak Butters | Port Adelaide | 25 | 27 |
| Errol Gulden | Sydney Swans | 24 | 27 |
| Tim Taranto | Richmond | 23 | 19 |
| Connor Rozee | Port Adelaide | 22 | 21 |
| Caleb Serong | Frementle | 21 | 24 |
| Zach Merrett | Essendon | 21 | 17 |
| Noah Anderson	| Gold Coast Suns	| 20 | 22 |
| Toby Greene	| GWS Giants | 19 |	20 |
| Darcy Parish | Essendon	| 19 | 15 |
| Jack Sinclair | St Kilda | 18 |	21 |
| Charlie Curnow | Carlton | 17 |	17 |
| Chad Warner	| Sydney Swans | 16 | 16 |
| Jeremy Cameron | Geelong Cats	| 16 | 13 | 
| Jack Viney | Melbourne | 15	| 24 |
| Rory Laird | Adelaide Crows	| 15 | 20 |
| Taylor Walker	| Adelaide Crows | 15 | 16 |


## Contents
- `AFL.Brownlow.Prediction.Model.html`: The knitted html document containing the analysis code.
- `AFL.Brownlow.Prediction.Model.Rmd`: The R Markdown document containing the analysis code.
- `AFLBrownlowPredictor.Rproj`: R project file for the AFLBrownlowPredictor project.
- `brownlow_data.csv`: A csv file containing the data required to run the model
- `README.md`: This file providing an overview of the repository.

