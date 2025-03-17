# LoLytics
End-to-End Data Engineering Pipeline for generating player stats and predictions

The goal here is to create a live dashboard with periodic updates (could be real-time, but for cost efficiency).
Web application having a ML model for my own stats would be fun.

## Data Source

Match Data is collected through Riot's official API. Their API documentation can be found [here](https://developer.riotgames.com/apis).

## Data Pipeline

### Azure Data Factory

#### Data Ingestion
- Batch Data: Time Range here (About 500 games)
- Streaming Data: Time Interval here
