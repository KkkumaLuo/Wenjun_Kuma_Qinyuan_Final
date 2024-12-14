# Analyzing the Best Restaurants for Dating in New York City
## Dataset(s)
The primary dataset for this project will be Google Reviews, which provides detailed customer feedback, ratings, and metadata for restaurants in New York City. We plan to extract this data using the Outscraper API. Supplementary data will include median household income at the neighborhood level (from U.S. Census data), public transit locations (from NYC Open Data), parking availability (from OpenStreetMap), and social media engagement metrics sourced from platforms like Instagram. 

## Research Question
Our project aims to answer the question: "What makes an ideal restaurant for couples to go on a date?" Specifically, we will identify the top 10 restaurants in New York City for dating based on reviews and evaluate why these establishments are popular. The analysis will explore factors such as proximity to public transit or parking, median income of the neighborhood, cuisine type, and social media engagement metrics. Through this study, we seek to provide actionable insights into the characteristics that define an ideal dating spot.

## Analysis Methods and Techniques
Our project will use API-based scraping for Google Reviews to collect base dataset. After acquiring the data, we will clean all of those review texts and using NLP tech, we will filter reviews with keywords such as romantic, couple, and date. Sentiment analysis will classify these reviews into several categories or grade them to assess customer opinions on ambiance, service quality, and overall experience and if it's ideal for dating.

After reviewing and preliminarily categorizing restaurant ratings, we will analyze the factors that make these restaurants particularly appealing to couples. Geospatial analysis tools such as GeoPandas and OSMnx will be utilized to assess proximity to public transit, parking availability, and the density of competing restaurants within the same neighborhood. Additionally, statistical and machine learning techniques—including clustering and regression—will help us group similar restaurants and uncover predictors of popularity. Finally, we will present our findings through interactive dashboards and maps to ensure effective communication of the results.

## How This Satisfies Final Project Requirements
Data collection will be conducted through advanced means, including scraping Google Reviews via the Outscraper API and integrating additional datasets from public sources like NYC Open Data. The Google Reviews dataset alone is expected to contain millions of rows, satisfying the requirement for working with a large dataset. We will also combine data from at least three sources: Google Reviews, Census data, and NYC Open Data. 

The analysis will be sufficiently complex, incorporating NLP-based sentiment analysis, geospatial joins, and k-means clustering. We will perform a geospatial analysis using tools like Osmnx to evaluate restaurant accessibility and neighborhood characteristics. Additionally, the project will include interactive visualizations through dashboards and maps.

The published site for this repository is available at:[https:/KkkumaLuo.github.io/Wenjun_Kuma_Qinyuan_Final/](https://KkkumaLuo.github.io/Wenjun_Kuma_Qinyuan_Final/).
