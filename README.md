__In this project, we will work on data cleaning and visualization for a data set containing applications on the Play Store.
This project involves analyzing applications available on the Play Store using Python libraries such as pandas, seaborn, and matplotlib.__

## Introduction to the Data
* First 5 Rows of the Data
* Random 5 Rows from the Data
* Number of Rows and Columns in the Data
* General Information about the Data
* Column Names in the Data
* Number of Null Values
## Data Cleaning and Processing
* Renaming Columns
* Replacing Missing Values with Mean
* Removing Missing Values
* Changing Data Types
* Combining similar values
* Preparing Data for Visualization
## Data Analysis
* Mean and Median Values for Rating, Reviews, and Installs columns
* Type values counts
* Content Rating Counts
* Total Downloads by Category
* Average Metrics by Category
* Average Rating by Content Rating
## Data Visualization
* Payment Information and App Rating
* App Rating by Type
* Content Ratings and App Ratings
* Number of Apps per Category
* Price and Category Relationship
## Summary with Visualizations
__Free vs. Paid Apps Free Apps:__ A large number of apps are free. Paid Apps: Paid apps usually have higher average ratings and a higher median rating than free apps. While both types of apps have outliers, they are more common among free apps. Free app ratings vary more, whereas paid apps have higher ratings within a narrower range.

__App Categories Most Apps:__ The "Everyone" category has the most apps, with over 8,000. Categories like "Teen" and "Mature 17+" have fewer apps. Categories like "Everyone 10+", "Adults only 18+", and "Unrated" have even fewer apps. Average Ratings: The "Adults only 18+" and "Unrated" categories have relatively high average ratings. Outliers are seen in the "Everyone 10+" and "Mature 17+" categories, showing some apps are rated very differently. Most ratings are in the 4-5 range.

__Popular App Categories Most Apps:__ The "FAMILY" category has over 2,000 apps. Other categories like "GAME", "TOOLS", "MEDICAL", and "BUSINESS" also have many apps. Fewer apps are in categories like "BEAUTY", "COMICS", and "AUTO_AND_VEHICLES".

__Paid App Categories Top Categories:__ The most paid apps are in the finance, lifestyle, and family categories.

__Correlations Rating and Reviews:__ There is a moderate correlation (0.66) between ratings and reviews, meaning apps with more reviews generally have higher ratings. Installs and Reviews: There is a strong correlation (0.86) between installs and reviews, suggesting apps with more installs get more reviews. Price: The correlation between price and other variables (rating, installs, reviews) is very weak, indicating price has little to no effect on these factors.

The dataset used in this project is sourced from Kaggle.  
