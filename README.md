# Chess Data Analysis

This data science project explores three datasets of chess games scraped from the internet. А diverse range of tools from the Python ecosystem is used to analyze the data and uncover meaningful trends.

## Project Structure
- **`data_acquisition_and_cleaning.ipynb:`**: scraping, preparing and cleaning the data
- **`data_exploration_and_analysis.ipynb:`**: exploration and analysis

### Some Visual Results:
Heatmap of squares on which queens are most often placed:
<p align="left">
  <img src="data/queen_heatmap_lichess.png" width="570"/>
</p>

The chessboard with piece position color-encoded for ResNet50 with legend:
<p align="left">
  <img src="data/chessboard_color_encoded.png" width="570"/>
</p>

Cosine similarity of color-encoded chess positions from move 10 to move 60 according to ResNet50:
<p align="left">
  <img src="data/cosine_similarity_plot.png" width="570"/>
</p>



### Summary of Findings:

- Is the player playing with the white pieces or the player playing with the black pieces favored to win, or is a draw the most likely outcome of the game?<br> 
White enjoys an advantage in all the datasets and this advantage grows quite large as skill level increases.<br> The percentage of drawn games increases greatly with a stronger player pool.
- How common are upsets in chess? Are upsets with a higher gap in rating between the opponents correspondingly rarer?<br> 
In engine chess upsets are much less common overall. In the dataset where there is specific tournament pairing dynamic (ChessCom) smaller upsets are less likely to happen, because of many "mismatches" and less opportunity of small upsets.
- What are the "hot" and "cold" spots on the chess board for different pieces(squares on which the piece is placed often or rarely)?<br>  Results can be seen in the heatmaps.
- Is it important to control and fight for the center of the board in a chess game?<br> 
Controlling the center might be a small contributing factor to the outcome of the game.
- How does the similarity between board states in different games evolve through the course of a long game?<br> 
In a limited experiment with a tiny sample size the similarity continues to decrease over the course of the game at least up to move 60.








