Webscraped Data from NBA API and Basketball Reference to collect offensive, defensive, and advanced statistics for 500+ players from the 2021-2024 season, including anything from PPG to VORP.

The data was then concatenated into a Pandas DataFrame and then cleaned and formatted in a way such that all players' names displayed correctly and data without a value was then cleared and removed from the DataFrame.

Trained XGBoost Logistic Regression Model on the data collected by finding the probability that each player makes an All-NBA team. The five players with the highest probability make first team, the next five 
highest players make second team, and the next five highest players make third team. This had a 93% player accuracy for the 2024-2025 All-NBA teams.

