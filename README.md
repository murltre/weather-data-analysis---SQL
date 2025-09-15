
## Extreme Weather SQL Analysis 🌦️
This project is part of a practice data analytics series designed to help strengthen SQL and data storytelling skills with real datasets. The focus of this project is Extreme Weather Data Analysis, where the goal is to practice querying a weather database, extracting meaningful insights.


## 🔹Project Overview

* Dataset: weather.db (SQLite) with three tables:

*daily_weather* – daily observations (temps, wind, precipitation)

*stations* – station metadata (only one station in this dataset)

*thresholds* – definitions of “extreme” conditions

## *Tools Used:*

- DB Browser for SQLite (SQL queries)

- Power BI (visualizations)

- Excel/CSV export



<img width="1485" height="377" alt="image" src="https://github.com/user-attachments/assets/8e0157f0-5274-4439-b845-7a6fc0f3ff59" />

<img width="532" height="302" alt="image" src="https://github.com/user-attachments/assets/3fb1f49e-a050-4b24-89df-e7d6d97e5185" />



## 🔹Key Analysis Questions

*1) How many days of data are recorded in total?*

*2) What was the highest temperature recorded, and on what date?*

*3) What was the lowest temperature recorded, and on what date?*

*4) How many days each year had extreme heat (temperature > 90°F)?*

*5) How many days each year had extreme cold (temperature < 32°F)?*

*6) What is the average wind speed for each year?*

*7) On how many days did wind speeds exceed 20 mph?*

*8) How many extreme weather days (heat > 90°F, cold < 32°F, or wind > 20 mph) occurred?*

*9) Which month had the highest number of extreme weather days?*

*10) What percentage of all recorded days were extreme weather days?*


 #Sample answer:

<img width="570" height="173" alt="image" src="https://github.com/user-attachments/assets/b906960e-8257-4cfe-9a14-27dd65f55da1" />

<img width="470" height="261" alt="image" src="https://github.com/user-attachments/assets/213fa78d-aecf-4f43-a7f3-51b055a4f735" />




## 🔹Visualization Insight

- The line chart shows a seasonal temperature cycle — highs peak in July/August, lows dip in Jan/Feb.

- Wind speeds are mostly steady (0–10 mph), with small spikes in March and July.

- July stands out as the hottest and windiest month; Jan–Feb mark the coldest lows.

- Per the answer to Q10, around **72%** of all days were classified as extreme weather days in 2023.

- Per the answer to Q9, **October** had the highest number of extreme days with **28 days**, followed by July with **26 days**


## For a deeper analysis, the data might need further investigation since we have some *tmax_f* maximum temp to be lower than *tmin_f* on some days


<img width="1114" height="645" alt="image" src="https://github.com/user-attachments/assets/747a0113-1f44-4c41-82a6-9f7d46fc1890" />



## 📂 Repository Contents

weather_analysis.sql → SQL queries

visuals/ → Power BI screenshots

Project works.pdf → Full report with queries and detailed answers

## View the full project in the PDF File



