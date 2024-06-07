## Google Play Store Apps Data Analysis
This repository contains an exploratory data analysis (EDA) of a dataset of Google Play Store apps. The dataset includes information on various app characteristics such as category, rating, reviews, size, installs, price, content rating, genres, last updated date, current version, and required Android version.

## Dataset
The dataset used in this analysis can be found here. It contains 10,841 entries with the following columns:

App
Category
Rating
Reviews
Size
Installs
Type
Price
Content Rating
Genres
Last Updated
Current Ver
Android Ver

Linke dataset: https://www.kaggle.com/datasets/lava18/google-play-store-appsSome initial observations:

## EDA
The "Rating" column has missing values.
The "Reviews", "Size", "Installs", and "Price" columns need conversion to numerical formats for analysis.
There are a few missing values in "Type", "Content Rating", "Current Ver", and "Android Ver".
Next, we'll clean the data and perform exploratory data analysis (EDA) to answer common business questions. Here are some typical questions we can address:

What are the most common categories of apps?
What is the distribution of app ratings?
How do app sizes vary across categories?
What is the relationship between the number of reviews and the app rating?
What are the most common genres?
How do free and paid apps compare in terms of ratings and number of installs?

## Analysis and Insights
1. Most Common Categories of Apps
![Top 10 Most Common App Categories](https://github.com/MissNeerajSharma/Data_Visualization_using_Python/blob/master/1.png)

The most common app categories are dominated by "Family", followed by "Game", "Tools", "Medical", and "Business".

2. Distribution of App Ratings

The majority of apps have ratings between 4.0 and 4.5, indicating that most apps are well-received by users.

3. Variation of App Sizes Across Categories

There is considerable variation in app sizes across different categories. Categories like "Game" and "Family" have a wider range of app sizes, while "Medical" and "Business" tend to have smaller sizes.

4. Relationship Between Number of Reviews and App Rating

There is no clear correlation between the number of reviews and the app rating. Apps with a very high number of reviews tend to maintain high ratings, but there are outliers.

5. Most Common Genres

The most common genres include "Tools", "Entertainment", "Education", "Business", and "Productivity".

6. Comparison of Free and Paid Apps
Ratings
![Comparison of Free and Paid Apps by Rating]()
Free and paid apps have similar ratings, with a slight edge towards free apps.

Installs

Free apps generally have a higher number of installs compared to paid apps, which is expected due to the cost barrier.

## Recommendations
App Development: Focusing on popular categories like "Family", "Game", and "Tools" could be beneficial due to high user interest.
Marketing: Emphasizing the unique features and quality can help apps stand out, particularly in crowded categories.
Pricing Strategy: Offering a free version with optional in-app purchases might attract more users and increase installs.
