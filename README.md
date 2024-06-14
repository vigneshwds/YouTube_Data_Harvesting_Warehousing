# Youtube data Harvesting and Warehousing using SQL and Streamlit

## Project Overview
This project demonstrates how to harvest data from YouTube and store it in a PostgreSQL database. It uses the YouTube Data API to collect information about channels, videos, and comments. The data is then stored in a PostgreSQL database for analysis and retrieval.

## Features
- Retrieve channel information including name, subscriber count, view count, and total videos.
- Extract video details such as title, description, tags, view count, like count, and comments.
- Store harvested data in a PostgreSQL database.
- Provide a web interface using Streamlit for data display and basic interactions.

## Technologies Used
- Python
- YouTube Data API
- PostgreSQL
- Streamlit
- Pandas
- Google API Client Library
- Plotly Express

## Setup and Installation
## Prerequisites
1. Python 3.7 or higher
2. PostgreSQL
3. Google API Key with access to YouTube Data API

## Install the required Python packages
1. pip3 install google-client-api
2. pip install psycopg2
3. pip install pandas
4. pip install streamlit
5. pip install plotly_express==0.4.0

## Set up PostgreSQL
1. Create a database in PostgreSQL.
2. Update the database connection details in the script (host, user, password, database, port).

## Obtain a YouTube Data API key
1. Go to the Google Developers Console.
2. Create a project and enable the YouTube Data API.
3. Create credentials to get an API key.
4. Replace the api_key in the Connect_Api function with your API key.

- ## Contact
If you have any questions or feedback, please reach out to vigneshoffical861@gmail.com.
