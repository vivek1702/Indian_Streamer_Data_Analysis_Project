# Indian_Streamer_Data_Analysis_Project

## Indian YouTube Gaming Streamers Data Analysis

This project involves extracting data from the top 92 gaming channels on YouTube in India. The data was obtained using the Google API client and analyzed using Python along with libraries such as Pandas and Matplotlib.

### Data Extraction

The following information was extracted for each channel:
- Channel title
- Video title
- Description
- Tags
- Published date and time
- View count
- Like count
- Favorite count
- Comment count
- Video duration
- Video definition
- Caption availability

### Exploratory Data Analysis (EDA)

During the EDA process, the following steps were performed:

1. Changing Data Types: The data types of certain columns were modified to ensure accurate analysis.
2. Date and Time Analysis: The published date and time were used to extract the year and week, allowing for temporal analysis.
3. Deleting Irrelevant Columns: Columns that were not relevant to the analysis were removed to streamline the dataset.

### Visualizations

Several visualizations were created to gain insights from the data:

1. View Distribution of Channels: This visualization depicts the distribution of views across different channels, providing an overview of popularity.
2. Analysis of Like Count and Comment Count: This visualization explores the relationship between the number of likes, comments, and the number of views, determining their impact on popularity.
3. Most Played Games by View Count: This analysis identifies the games that received the highest view counts, indicating the most popular games among Indian YouTube gaming streamers.
4. Number of Different Games Played Over the Years: This visualization shows the number of different games played by Indian YouTube gaming streamers over the years, highlighting trends and preferences.
5. Time Frame Analysis: This visualization displays the time frames during which the most number of gaming videos were uploaded, uncovering peak activity periods.
6. Weekday Analysis: This visualization identifies the weekdays with the highest number of gaming video uploads, revealing patterns in streamer behavior.
7. Average Video Length: This analysis calculates the average length of gaming videos, providing insights into viewer preferences.

Please refer to the Jupyter Notebook in this repository for a detailed explanation of the data extraction, EDA process, and visualizations.

uploaded data into kaggle for reference - https://www.kaggle.com/datasets/rabbtort17/youtube-data-indian-gamers
