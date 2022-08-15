# Surfs Up Weather Analysis

## Project Overview
A potential investor wants to learn more about the weather of Oahu, an island in Hawaii, before committing to build a Surf and Ice Cream shop. The investor's main concern is the island's temperature/weather won't provide ideal weather conditions for the business to be sustainable year-round. We analzyed Oahu's weather data using **SQLAlchemy** to connect to and queary a **SQLite database** and ran weather statistics for the months of June and December to assist with the investor's decision making process.

## Results

The tables below represent June and December's temperature statistice over time. Temperatures are measured in degrees of Fahrenheit.

![June_temps](https://user-images.githubusercontent.com/107579508/184689354-72993ceb-826d-40a5-9ac5-01cdd1b1a77a.png)

![December_temps](https://user-images.githubusercontent.com/107579508/184689385-f5e28e87-05e2-463f-9a58-ad9e593aa26c.png)

Key Points:
 - Mean temperature between June and December is approximately **75** and **71** degrees fahrenheit respectively. This is a small fluctuation and provides ideal temperatures for this business model to sustain itself.
 - The maximum temperatures of **85** (June) and **83** (December) degrees are also remarkably similar and provide ideal temperatures for surfing and ice cream consumption.
 - The minimum temperatures of **64** (June) and **56** (December) degrees show the greatest variance and may not be conducive to ice cream consumption. However, it should not cause great concern as these temperatures are likely experienced outside of the normal operating hours anyway.

## Summary

The overall temperature data in Oahu for the months of June and December are historically very similar especially in comparison to other climates around the world and provide ideal temperatures to sustain the business model year-round.

Additional queries that have been completed include comparing precipitation data for June and December. These statistics provide additional insight to determine if certain parts of the year cause more rain as well as other limiting factors.

Below are two queries that show June and Decembers precipitation data.
NOTE: The most common rainfall measurement is expressed in millimeeters (mm) and these statistics are a reflection of this.
 
 ![June_prcp](https://user-images.githubusercontent.com/107579508/184692602-70bd55b0-3f8c-4cfc-af20-ece1732af9e7.png)

 ![December_prcp](https://user-images.githubusercontent.com/107579508/184692629-3ad3ac98-bd93-4a9d-90c4-c7d862701a00.png)
