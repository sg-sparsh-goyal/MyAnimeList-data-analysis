# Anime Dataset Analysis
This project involves web scraping [`MyAnimeList`](https://myanimelist.net/) (MAL) and performing data analysis on the collected anime dataset.

## Web Scraping
The web scraping script fetches the data from an anime database, collecting detailed information about each anime. 

The scraping is performed using the [`BeautifulSoup`](https://pypi.org/project/beautifulsoup4/) library of python.

The script ensures that the data is accurate and up-to-date.The dataset was scraped season wise from Winter 2023 to Summer 2024. The dataset includes various attributes such as Title, Theme, Studio, Source, Episodes, Rating, Members, Date, and Img_url.

## Data Analysis
The analysis script performs various data cleaning, preprocessing, and visualization tasks. Key features include:

- **Data Cleaning**: Handling missing values and outliers using the Interquartile Range (IQR) method.
- **Data Visualization**: Creating customized and aesthetically pleasing plots using [`Plotly`](https://plotly.com/python/), with specific color schemes and styles.
- **Insight Extraction**: Analyzing trends in anime ratings over the years and identifying popular themes and studios.
- **Clustering**: Performed clustering of anime titles with the help of [`K-means`](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html) algorithm

To View the data analysis notebook [click here](https://nbviewer.org/github/sg-sparsh-goyal/MyAnimeList-data-analysis/blob/master/MAL_data_analysis_and_clustering.ipynb): 


## How to Use
- Clone the repository.
- Run the web scraping script to collect the data.
- Use the analysis script to clean, visualize, and analyze the data.

