# Spotify Data Analysis

## Introduction

This project involves the analysis of data related to Spotify listeners. The goal is to explore and visualize insights from this dataset, which provides information about the number of listeners, daily trends, and peak positions for various artists on Spotify.

## Data Collection

- **Web Scraping**: I collected the data by scraping the web using Python. The data source is the website [kworb.net](https://kworb.net/spotify/listeners.html), which displays the daily statistics of Spotify listeners for artists. However, it's important to note that this source changes daily.

- **API Documentation**: The web scraping process was performed using Python libraries, including [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) for parsing HTML content.

## Data Attributes

The dataset consists of the following attributes:

1. **Artist** (Data Type: Object): The name of the artist on Spotify.

2. **Listeners** (Data Type: Integer): The number of listeners for the artist.

3. **Daily Trend** (Data Type: Integer): The change in the number of listeners for the artist within one day.

4. **Peak Position** (Data Type: Integer): The highest position reached by the artist on Spotify charts.

5. **PeakListeners** (Data Type: Integer): The number of listeners at the artist's peak position.

## Data Analysis

- **Descriptive Statistics**: I calculated basic descriptive statistics for the dataset to understand its central tendencies, variations, and distributions.

- **Data Visualization**: I created various data visualizations, including bar charts, scatter plots, and box plots, to provide insights and facilitate the interpretation of the data.

## Analysis and Observations

- **Top Artists**: I identified the top artists by the number of listeners, both in current listeners and peak listeners. This can help identify the most popular artists on Spotify.

- **Daily Trend vs. Peak Position**: I explored whether there was a correlation between the daily trend in listeners and the peak position on Spotify charts. The scatter plot revealed no significant correlation, suggesting that an artist's daily trend doesn't necessarily impact their peak position.

## Known Issues/Quirks/Biases

- The data may not capture long-term trends, as it provides daily statistics, and the dataset is limited to 200 rows out of the 2500 rows/artists.3

## Dependencies

- The analysis was conducted using Python and the following libraries: `requests`, `BeautifulSoup`, `pandas`, `numpy`, `scipy`, and `matplotlib`.
