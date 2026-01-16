# 📊 YouTube Data Harvesting & Warehousing

A Streamlit app to extract YouTube channel data using the YouTube Data API, store it in MongoDB, migrate it to PostgreSQL, 
and perform SQL-based analysis with visualizations.


🚀 Features

- Fetch channel, playlist, video & comment data
- Store raw data in MongoDB
- Migrate structured data to PostgreSQL
- Run analytical SQL queries
- Interactive dashboard using Streamlit & Plotly


🛠 Tech Stack

Python, Streamlit, YouTube Data API, MongoDB, PostgreSQL, Pandas, Plotly


🗄️ Databases

MongoDB: Data lake (Youtube_data)

PostgreSQL: Data warehouse (youtube_data)

Tables: channels, playlists, videos, comments


▶️ Usage

Enter a YouTube Channel ID.

Click Collect and Store Data.

Select channel → Migrate to SQL.

Run queries & view charts.


📊 Analytics Includes

Top viewed videos

Channels with most videos

Likes, comments, views analysis

Videos published in 2022

Avg duration per channel



🔄 Workflow

1. Data Collection

Enter a YouTube channel ID

Fetches:

Channel Information

Playlist Information

Video Metadata

Comments

Stored in MongoDB under Youtube_data.channel_details.

2. Migration to SQL

Transfers data into PostgreSQL tables:

channels

playlists

videos

comments

3. Data Exploration

Choose from predefined SQL queries such as:

Most viewed videos

Channels with highest video count

Videos with max likes

Comments per video

Videos published in 2022

Average video duration per channel

All results are displayed as tables and visual charts.


📁 Project Structure

youtube.py           # Main Streamlit app and ETL logic
youtubetest.ipynb    # Notebook (optional/included by user)


🔑 Requirements

Valid YouTube Data API key
MongoDB Atlas or local MongoDB
PostgreSQL database named youtube_data


📙 Summary

This project demonstrates a complete pipeline:
API → MongoDB → PostgreSQL → Streamlit Analytics
Ideal for data engineering, ETL, data warehousing, and dashboarding practice


# 👤 Author

Venkatesan M

