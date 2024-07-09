# AFLBrownlowPredictor
This project dives into predicting the 2023 AFL Brownlow Medal votes, using a data I compiled from various sources such as the `fitzRoy` R package, afl.com.au, AFL Tables, and the AFL Coaches Association. By incorporating a range of offensive and defensive statistics, team metrics, AFL Coaches Association votes, as well as variables regarding past recognition such as previous Brownlow performances; my model aims to capture the key aspects of player performance, allowing for a nuanced understanding of what contributes to recognition from the umpires.

The repository contains an R Markdown document and associated files for leveraging an ordinal logistic regression model to predict the 2023 Brownlow Medal votes awarded to players in each AFL game, based on game statistics and other metrics.

## Results
The analysis of the predictions compared to the actual votes for the Brownlow Medal revealed several important insights into the model’s performance. While the model didn’t correctly predict the eventual winner in Lachie Neale (an outside chance according to bookmakers), in terms of error metrics the difference between the model’s predicted votes and the actual votes for each player is quite accurate.
• When taking a subset of players who I predicted to poll votes and/or actually polled votes (removing players who were predicted to poll 0 votes and also actually polled 0 votes as this would provide a false sense of accuracy), the Mean Absolute Error (MAE) was 2.165, indicating that, on average, the predicted votes differ from the actual votes by about 2.165 votes.
• The model also correctly predicted the player to poll 3 votes in 56.52% of matches (117 out of 207).

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
| Caleb Serong | Fremantle | 21 | 24 |
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

