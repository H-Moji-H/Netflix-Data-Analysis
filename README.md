# Netflix Data Analysis

## Introduction

In today's digital age, streaming services like Netflix have revolutionized entertainment consumption. To better understand Netflix's content strategy and trends, an in-depth analysis of the available shows and movies was performed on their platform. The project explores key insights such as content type distribution, release trends, ratings, genres, and popular production countries.

## Objective

The primary objectives are:

•	To understand the distribution and evolution of Netflix content over time.

•	To explore the genres, ratings, and countries dominating the platform.

•	To identify trends in content addition, audience targeting, and production patterns.

•	To visualize key patterns and present actionable insights from the Netflix catalog data.

## Dataset Overview
The dataset used for this analysis was sourced from Kaggle ("Netflix Shows" by Shivamb).

•	Size: 8807 entries, 12 columns.


It contains information about Netflix titles. Its features include:

     o	type: Movie or TV Show

     o	show_id, title, director, cast, country, date_added, release_year, rating, duration, listed_in, description

The dataset provides metadata about Netflix’s catalog up to 2021 thus offering rich opportunities for exploration and trend discovery.

## Feature Engineering

•	Converted the date_added column to proper datetime format.

•	Extracted new features:

     o	year_added (Year content was added to Netflix)
     o	month_added (Month name content was added)
    
•	Separated duration into:

    o	duration_num (Numerical part: minutes or seasons)
    o	duration_unit (Unit: minutes, season(s))
    
This transformation helped streamline the time-based and duration-based analyses.

## Exploratory Data Analysis (EDA) and Insights

### 1. Content Type Distribution

•	Movies dominate the Netflix catalog with over 6000 titles, while TV Shows are fewer but still significant (~2500 titles).

### 2. Content Added Over the Years

•	Content additions rose sharply from 2015.

•	Peaked in 2019 with over 2000 titles added.

•	Reflects Netflix's aggressive expansion strategy leading into 2020.

### 3. Release Year Distribution

•	The number of releases steadily grew.

•	2019 recorded the highest number of releases, exceeding 3500.

### 4. Ratings Distribution

•	TV-MA (Mature Audiences Only) is the most common rating, 
suggesting Netflix leans heavily into mature content.

•	G (General Audience) is the least frequent.

### 5. Top Production Countries

•	USA leads by a large margin (~2500 titles).

•	India follows, contributing about 1000 titles, showcasing growing international content.

### 6. TV Shows Seasons Analysis

•	Most TV Shows have only 1 season, with over 1750 entries.

•	Indicates a trend towards short-format series or pilot seasons.

### 7. Genre Analysis

•	Top Genres include :

    o	International Movies
    o	Dramas
    o	Comedies
    
•	Highlights a strong focus on globally appealing and emotionally engaging content.

### 8. Word Cloud Analysis of Descriptions

•	Common words: 

          life 
          find 
          family 
          love
          world

•	Thematic emphasis on relationships, discovery, and human experiences.

### 9. Content Added by Month

•	July is the most popular month for adding new content.

•	February sees the least content additions.

## Key Findings

•	Genres like international 
movies, dramas, and comedies are most prevalent.

•	Netflix's growth trajectory accelerated from 2015, peaking before the COVID-19 pandemic(2019).

•	Content released in 2019 was exceptionally high.

•	Content strategy favors mature audiences(TV-MA) and international expansion.

•	Movies far outnumber TV Shows.

•	The USA and India are the top contributors to Netflix’s catalog.

•	July tends to have the highest number of content uploads. 
This could be a strategic month for Netflix releases, possibly to capture summer viewership.

## Results
This exploratory analysis provides a comprehensive overview of the Netflix content landscape. It highlights growth patterns, user preferences (via ratings and genres), and international contributions to Netflix’s ever-growing catalog.

•	Netflix focuses heavily on short-format TV shows, mature audiences, and international genres.

•	USA and India dominate production, but there's a healthy diversity of countries contributing.

•	Monthly content additions suggest strategic planning, not random uploads.

## Conclusion

Netflix has evolved from a regional service to a global entertainment powerhouse with diversified content. 
Understanding the trends in content types, genres, and production origins helps content strategists, marketers, and researchers understand both the past and future trajectory of streaming content.

The Netflix catalog exhibits clear trends in content type, target audience, and production origins. The platform emphasizes mature audiences, internationally themed entertainment, while balancing between movies (majorly) and limited-series TV shows. 
The data reveals that Netflix sources a lot of content from the United States and India. It also reveals that strategic timing, genre diversity, and audience segmentation are core to Netflix's continued growth and global dominance.

### Future analysis could involve:

1.   Further Sentiment analysis of content descriptions.

2.	Time series forecasting for future content additions.

3.	Audience engagement analysis using viewership data.





