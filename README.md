# Wine Reviews Analysis
This project revolves around a comprehensive analysis of over 130k wine reviews encompassing a multitude of attributes including variety, location, winery, pricing, and descriptive critiques. This analysis paves the way to discern geographical distribution of wine production, discern vintage trends, understand rating systems, and gauge sentiment tied to reviews. The comprehensive dataset empowers us to delve into textual critiques to extract sentiment and key descriptive terms, all of which can be instrumental for winemakers, marketers, and connoisseurs in appreciating wine from a data-driven perspective.

The data encompasses wines from a variety of countries and provides a rich corpus of text in the form of sommelier reviews. The project encapsulates the source code, datasets, and visual outputs derived from the analysis.

## Objectives:
1. Explore the geographical distribution and density of wine origins.
2. Analyze vintage trends among the 130k+ wines, identifying popular production years.
3. Understand the rating system and its correlation with price.
4. Employ sentiment analysis on wine reviews to categorize sentiments as positive, neutral, or negative.
5. Extract commonly used terms and phrases from the reviews to identify popular descriptors.
6. Generate visualizations to represent the findings in a more intuitive and comprehensible manner.

## Dataset Exploration:
Acquisition: The dataset used for this analysis comprises 130k+ wine reviews, each enriched with attributes such as country of origin, price, rating, winery, and a detailed description by sommeliers.

Data Wrangling: Leveraging libraries like pandas and seaborn for cleaning, transforming, and visualizing the dataset to ensure it's well-suited for subsequent analysis.

Basic Statistics: Generating basic statistics to understand the data distribution across different dimensions like country, price, and ratings.

## Text Mining:
Preprocessing: Implementing preprocessing steps such as tokenization, stopword removal, and stemming to prepare the text for analysis.

Top Terms Extraction: Identifying and visualizing top terms using Word Clouds to understand common descriptors used by sommeliers.

Sentiment Analysis: Employing TextBlob to perform sentiment analysis on reviews, and visualizing sentiment distribution across different rating scores and price points.

## Data Visualization:
Geographical Distribution: Creating interactive visualizations to depict the geographical distribution of wine origins, emphasizing regions with the highest concentration of brands.

Ratings and Price Analysis: Visualizing the relationship between ratings, price, and sentiment to derive insights on how these dimensions correlate.

Vintage Analysis: Investigating the distribution of production years, understanding the age of wines, and visualizing these trends.

## Libraries Used:
Data Manipulation: numpy, pandas

Data Visualization: seaborn, matplotlib, plotly

Text Mining: nltk, re, TextBlob

Machine Learning: sklearn

## Concluding Insights:
The analyses provide a multi-faceted understanding of the global wine landscape, shedding light on the geographical predominance of wine production, vintage trends, rating dynamics, and textual sentiments in reviews. This project hopes to serve as a foundation for further exploratory and predictive analysis in the domain of wine analytics, thereby aiding stakeholders in making informed decisions.

## Note:
This project is purely analytical and does not endorse any brand or type of wine. It's an attempt to understand the wine market through data and derive actionable insights.

## Usage:
Feel free to clone this repository, explore the dataset, and employ the provided code to carry out your own analysis. The code is structured to allow easy modification for analyzing different attributes or employing alternative methodologies.
