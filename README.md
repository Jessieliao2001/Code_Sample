# Python Data Analysis and Web Scraping Projects

This repository showcases various Python projects focused on data analysis and web scraping, covering tasks such as data processing, visualization, and dynamic web content extraction. Each project addresses unique challenges in data manipulation, text analysis, and automated data retrieval.

## Project Descriptions

### 1. Web Crawler for Movie Information

- **Description**: Extracts detailed movie information from web pages, including names, genres, and ratings, and saves this information into a CSV file.
- **Challenges**: Managing pagination, avoiding IP blocks, and dynamically fetching content required robust error handling.
- **Solution**: Used BeautifulSoup for HTML parsing, with randomized delays and proxy management to ensure stable data retrieval.
- **Output**: CSV file containing detailed movie metadata, facilitating further analysis【11†source】.

### 2. Web Scraping with Selenium

- **Description**: Automates the extraction of user comments from Douban’s movie review pages, integrating Selenium for navigation and Requests for HTTP handling.
- **Challenges**: Douban’s website contains dynamic content and access restrictions, requiring careful setup of headers, cookies, and random delays.
- **Solution**: Implemented a hybrid approach using Selenium for JavaScript-rendered content and Requests for direct data retrieval, with proxy management and error handling to address access issues.
- **Output**: CSV files containing user comments, ratings, and profile information【9†source】.

### 3. Word Cloud Visualization

- **Description**: Generates word clouds to visualize the most common words in movie comments, categorized by satisfaction levels and genres.
- **Challenges**: Handling extensive text data in Chinese required efficient text segmentation and stopword filtering.
- **Solution**: Utilized jieba for segmentation, customized word clouds with WordCloud library, and encapsulated functionality for modular code organization.
- **Output**: Word clouds highlighting frequent themes across movie genres and satisfaction levels【10†source】.

### 4. Sentiment Analysis Visualization

- **Description**: Analyzes and visualizes sentiment data from movie reviews, identifying patterns across regions.
- **Challenges**: Processing diverse datasets, handling regional encoding (e.g., Chinese characters), and creating clear comparative visuals.
- **Solution**: Applied SnowNLP for sentiment analysis, structured DataFrame processing in Pandas to calculate sentiment proportions, and visualized regional sentiment with matplotlib using stacked bar charts for positive and negative sentiment proportions.
- **Output**: Visualizations showcasing sentiment distributions across regions, including average sentiment scores for each region【8†source】.

## Installation

1. Clone this repository.
2. Install the required Python libraries with:

   ```bash
   pip install -r requirements.txt
   ```

3. Run each script as per instructions in its respective directory.
