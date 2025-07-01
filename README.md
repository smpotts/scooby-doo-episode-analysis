# Scooby-Doo Episode Analysis

This project dives into the world of Scooby-Doo, using data from over 600 episodes and movies. It explores how different themes, characters, and catchphrases show up over time, and highlights the show's trends through data visualization.

## Data Sources

The data come from the [Kaggle Scooby-Doo Complete Dataset](https://www.kaggle.com/datasets/williamschooleman/scoobydoo-complete), which includes:
- `scoobydoo_episodes.csv` – metadata about each episode (title, date aired, runtime, network, IMDb score, etc.)
- `scoobydoo_monsters.csv` – monster-related attributes (monster type, gender, setting, capture details, quotes, snacks, etc.)

A PDF from the dataset author is also included, providing context and methodology for how the data was curated and feature-engineered.

## Cleaning Steps

- Standardized column names to snake_case
- Merged episodes and monster data into a unified dataframe
- Converted runtime to numeric values and imputed missing values by format averages
- Cleaned network and location columns for consistency
- Extracted and created features such as catchphrases-per-minute

## Exploratory Analysis

The notebook explores:
- IMDb score and engagement over time
- Catchphrase frequency (e.g., “zoinks”, “jinkies”) normalized by runtime
- Analyzing character activity
- Differences in runtime across formats (TV series vs. movies)
- Most common episode settings

## Visualization Highlights

- A bar plot showing how many monsters each character caught
- A bar plot showing how many monsters each character unmasked
- A bar plot showing how many snacks each character offered
- A line plot showing average engagement episodes received on IMDB over time

## How to Run

1. Clone this repo  
2. Create a virtual environment
3. Install dependencies:  
   ```bash
   pip install pandas matplotlib
4. Select a Python kernel and run the Jupyter notebook 
