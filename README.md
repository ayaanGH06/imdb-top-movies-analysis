# imdb-top-movies-analysis
A simple data science project exploring the IMDb Top Movies dataset. The notebook parses data from IMDb’s Top Movies list and performs basic analysis to uncover patterns, trends, and insights about ratings, genres, and popularity.

## Features
- Scrapes IMDb Top 250 movies using **BeautifulSoup**
- Extracts titles, release years, genres, ratings, and votes
- Saves cleaned dataset to **CSV** (`imdb_top_250.csv`)
- Performs exploratory analysis:
  - Missing value checks
  - Dataset summary (`df.info()`)
  - Initial insights on ratings, votes, and genres

## Tech Stack
- Python  
- Pandas, NumPy  
- BeautifulSoup (bs4)  
- Matplotlib  

## How to Run
1. Clone the repo:  
   git clone https://github.com/your-username/imdb-top-movies-analysis.git
   cd imdb-top-movies-analysis
2. Install dependencies:
   pip install -r requirements.txt
3. Open the Jupyter notebook:
   jupyter notebook imdb_analysis.ipynb
4. Run all cells to scrape IMDb and analyze the data.

📂 Files

- imdb_analysis.ipynb → Main analysis notebook
- imdb_top_250.csv → Exported dataset
