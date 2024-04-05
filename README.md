# Best Locations for Quality of Life


## Problem Statement


As the world becomes increasingly interconnected, more individuals are seeking opportunities to improve their quality of life by relocating to new destinations around the globe. The objective of this project is to identify which countries individuals should move to for better quality of life based on factors such as health, economy, and happiness.


## Data Dictionary


The data used in this study originated from the World Development Statistics from [Gapminder](https://www.gapminder.org/about/), an independent Swedish foundation that aims to make data about the world more accessible and reliable.


|Feature|Type|Dataset|Description|
|---|---|---|---|
|country|object|final_merged_data.csv|Name of country being studied
|2012_life|float|life_expectancy.csv|Number of years a person is expected to live in a particular country in 2012
|2022_life|float|life_expectancy.csv|Number of years a person is expected to live in a particular country in 2022
|2012_gni|int|gni_per_cap_atlas_method_con2021.csv|Gross National Income per capita (USD) in 2012
|2022_gni|int|gni_per_cap_atlas_method_con2021.csv|Gross National Income per capita (USD) in 2022
|2012_happiness|float|hapiscore_whr.csv|National average happiness score in 2012
|2022_happiness|float|hapiscore_whr.csv|National average happiness score in 2022


## Executive Summary

As the world becomes increasingly interconnected, more individuals are seeking opportunities to improve their quality of life by relocating to new destinations around the globe. The objective of this project is to identify which countries individuals should move to for better quality of life based on factors such as health, economy, and happiness. This study uses life expectancy, GNI, and happiness score data from [Gapminder](https://www.gapminder.org/about/) to achieve this goal. While performing the analysis, some countries were left out of the study if they had missing data in any of the 3 cateogories.  

During the study it was found that there is a positive correlation for GNI, life expectancy and happiness; therfore, countries with high scores across all three categories will theoretically offer the best quality of life. Due to this, it is recommended that people should relocate to nordic countries if they are looking for a better quality of life. They were consistently found in the top 10 of each category and placed in the top 5 when looking at all categories combined. The top 5 recommended countries are Finland, Denmark, Iceland, Sweden, and the Netherlands.

Since the data only goes up to 2022, I recommend furthering the study to include more up to date information to provide the best recommendations. In further studies, I'd also recommend looking at other factors outside of GNI, life expectancy, and happiness to get a more holistic outlook.
