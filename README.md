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








