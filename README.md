This project analyzes the performance of football forwards from Europe's top 5 leagues using statistical clustering.

## Project Description

The main goal is to identify distinct player profiles using Gaussian Mixture Models (GMM) based on performance statistics. The project includes the data, the clustering code, and visualizations of the results.

### Key Files
- `Europe_FWs_clustering.ipynb`: The main Jupyter Notebook for data processing and GMM clustering.
- `Top_complete_forwards_comparison.ipynb`: A notebook used for comparing the elite complete forwards cluster.
- `Europe_ATT_clusters/`: This folder contains the output CSV files with player cluster assignments and radar plots visualizing the average profile for each cluster.
- `all_clustered_forwards.xlsx`: A summary Excel file of all clustered players. Useful if you want to find what cluster a player is in without searching in every file

## Data
The player statistics used in this analysis were collected from [**FBref.com**](https://fbref.com/en/).
The raw player statistics are stored in a private file (`Players.xlsx`) and are not included in this repository due to potential licensing restrictions and file size.

However, the key outputs of the analysis, including the clustered player data and radar plots, are available in the `Europe_ATT_clusters/` folder and in `all_clustered_forwards.xlsx`.

### Data Schema
To allow others to understand the analysis, here is a description of the columns expected in the `Players.xlsx` file:

*   `PlayerName`: The name of the player.
*   `Age`: The player's age.
*   `Goals`: Number of goals scored.
*   `Assists`: Number of assists provided.
*   `xG` (Expected Goals): The quality of shots taken.
*   `PrgC` (Progressive Carries)
*   `Int` (Interceptions)
*   Other statistics all being per 90 minutes