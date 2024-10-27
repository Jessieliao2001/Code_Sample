# Python Data Analysis and Web Scraping Projects

This repository contains a selection of data analysis and web scraping scripts in Python. Each project demonstrates proficiency with data processing, visualization, and scraping dynamic web content. These samples reflect a hands-on approach to challenges in text analysis, sentiment visualization, and automation in data extraction.

## Project Descriptions

### 1. Sentiment Analysis Visualization

- **Description**: Analyzes and visualizes sentiment data from movie reviews, identifying patterns across regions.
- **Challenges**: This project required processing diverse datasets, dealing with regional encoding issues (e.g., handling Chinese characters), and implementing clear, comparative visuals.
- **Solution**: Applied SnowNLP for sentiment analysis, followed by structured DataFrame processing in Pandas to calculate sentiment proportions. Visualized regional sentiment with matplotlib using stacked bar charts to depict positive and negative proportions.
- **Output**: Visualizations showcasing sentiment distributions across regions, including average sentiment scores for each region【8†source】.

### 2. Web Scraping with Selenium

- **Description**: Automates the extraction of user comments from Douban’s movie review pages. Integrates Selenium for navigation and Requests for HTTP handling.
- **Challenges**: Douban’s website had dynamic content and access restrictions, requiring careful setup of headers, cookies, and random delays.
- **Solution**: A hybrid approach using Selenium for JavaScript-rendered content and Requests for direct data retrieval. Integrated proxy management and error handling to mitigate access issues.
- **Output**: CSV files containing detailed user comments, ratings, and profile information【9†source】.

### 3. Word Cloud Visualization

- **Description**: Generates word clouds to visualize the most common words in movie comments, categorized by satisfaction levels and genres.
- **Challenges**: Handling extensive text data in Chinese required efficient text segmentation and stopword filtering.
- **Solution**: Utilized jieba for segmentation, customized word clouds with WordCloud library, and encapsulated functionality for modular code organization.
- **Output**: Word clouds highlighting frequent themes across movie genres and satisfaction levels【10†source】.

### 4. Web Crawler for Movie Information

- **Description**: Crawls movie information including names, genres, and ratings from a paginated list on Douban.
- **Challenges**: Managing pagination, avoiding IP blocks, and dynamically fetching content required robust error handling.
- **Solution**: Used BeautifulSoup for HTML parsing, with randomized delays and proxies to ensure uninterrupted data retrieval.
- **Output**: CSV file containing detailed movie metadata, facilitating further analysis【11†source】.

## Installation

1. Clone this repository.
2. Install the required Python libraries with:

   ```bash
   pip install -r requirements.txt
   ```

3. Run each script as per instructions in its respective directory.
