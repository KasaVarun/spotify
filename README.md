# Spotify Data Analysis

This project explores and analyzes Spotify music data to uncover trends in song popularity, audio features, and relationships between musical characteristics over time. Using Python-based data analysis and visualization tools, it delivers insights useful for music recommendation, trend forecasting, and genre understanding.

## Project Objectives

- Load and clean Spotify music dataset
- Perform exploratory data analysis (EDA)
- Visualize trends in song popularity and attributes (e.g., energy, tempo, valence)
- Analyze correlation between audio features and popularity
- Identify characteristics of top songs and popular genres
- Provide insights for artists, listeners, and music platforms

## Tools and Libraries Used

- Python 3.x
- Pandas & NumPy
- Matplotlib & Seaborn
- Plotly (for interactive visualizations)
- Jupyter Notebook

## Dataset

The dataset includes tracks from Spotify with key features such as:
- `popularity`: popularity score (0-100)
- `danceability`, `energy`, `loudness`, `valence`, `tempo`, `speechiness`, etc.
- `release_date`, `year`, `artist`, `track_name`, `genre`

This dataset may have been sourced from Kaggle or Spotify’s API.

## Key Insights

- Danceability and energy tend to positively correlate with song popularity
- Popular songs often feature higher valence and tempo
- Genre and year significantly affect average popularity
- Visualizations reveal shifts in music style preferences over decades

## How to Run

1. Clone this repository
2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open and run the notebook:
   ```bash
   jupyter notebook "Spotify Analysis.ipynb"
   ```

## Author

**Varun Kasa**  
Master's in Information Systems, Northeastern University  
Email: varunkasa8@gmail.com  
GitHub:  https://github.com/KasaVarun

## License

This project is licensed under the MIT License.
