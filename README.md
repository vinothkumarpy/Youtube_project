

# YouTube Data Harvesting and Warehousing

## Introduction

This project is a comprehensive data science application that utilizes Python, MongoDB, MySQL, YouTube Data API, Streamlit, Pandas, Plotly, and VS Code. It aims to fetch and organize data from YouTube channels, store it in a MongoDB data lake, migrate it to a SQL data warehouse, and provide an interactive user interface using Streamlit.

## Problem Statement

For a detailed overview of the problem statement and project requirements, refer to the [Problem Statement Document](https://docs.google.com/document/d/1WrMDf4KnzprK37EJLr3QW0wRUB3few-1Yujv6wnYhZw/edit).

## Author Information

- **Name:** Vinothkumar S
- **Batch:** DTM2
- **Domain:** Data Science

## Features

1. **YouTube Data Retrieval:**
   - Input a YouTube channel ID and retrieve relevant data (Channel name, subscribers, total video count, playlist ID, video ID, likes, dislikes, comments of each video) using Google API.

2. **Data Lake in MongoDB:**
   - Store data in a MongoDB data lake for up to 10 different YouTube channels with the ability to click a button and collect the data.

3. **SQL Database Migration:**
   - Select a channel name and migrate its data from the data lake to a SQL database (MySQL or PostgreSQL).

4. **SQL Database Querying:**
   - Search and retrieve data from the SQL database using different search options, including joining tables to get channel details.

5. **YouTube API Integration:**
   - Utilize the YouTube API to retrieve channel and video data, leveraging the Google API client library for Python.

6. **Technologies Used:**
   - Python
   - MongoDB
   - MySQL
   - YouTube Data API
   - Streamlit
   - Pandas
   - Plotly
   - VS Code

## Getting Started

1. **YouTube API Setup:**
   - Obtain API key from [Google Cloud Console](https://console.cloud.google.com/) and enable YouTube Data API.

2. **MongoDB Setup:**
   - Install MongoDB and pymongo library.

3. **SQL Database Setup:**
   - Install MySQL or PostgreSQL and necessary Python libraries.

4. **Run the Application:**
   - Execute the main script to run the application.

## Usage

1. **Data Retrieval:**
   - Input YouTube channel ID and click a button to fetch data.

2. **Data Storage:**
   - Store data in MongoDB by clicking a button.

3. **Data Migration:**
   - Select a channel name and migrate data to SQL.

4. **Data Querying:**
   - Use the Streamlit app to search and retrieve data from the SQL database.

## Contributing

Feel free to contribute by opening issues, suggesting improvements, or submitting pull requests. Your input is highly valued!

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to customize the content based on your preferences or additional information you want to include.
