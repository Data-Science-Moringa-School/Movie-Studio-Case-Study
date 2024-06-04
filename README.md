

# DSC Phase One Project

**Author**: [Maureen Wanjeri](mailto:your.email@example.com)

## Overview

This project aims to analyze various aspects of the movie industry, including budgets, revenues, and ratings, using data from multiple sources. Through descriptive analysis and visualizations, we uncover trends and provide actionable insights for better decision-making in movie production and marketing.

## Business Problem



Understanding the key factors that drive movie success can help producers and marketers allocate resources more effectively. This project identifies these factors through data analysis and provides recommendations for optimizing production budgets, targeting the right audiences, and improving overall financial outcomes.

## Data

The project utilizes several datasets, including movie budgets, revenues, and ratings from different sources. Each dataset provides unique insights into various aspects of the movie industry.

- [Movie Budgets](./data/movie_budgets.csv)
- [Box Office Gross](./data/box_office_gross.csv)
- [IMDB Ratings](./data/imdb_ratings.csv)
- [Rotten Tomatoes Reviews](./data/rotten_tomatoes_reviews.csv)

## Methods

The analysis includes data cleaning, merging, and visualization using Python libraries such as Pandas, Matplotlib, and Seaborn. Key metrics and trends are identified through descriptive statistics and visual exploration.

## Results

### Average Production Budget Over Time

Analyzing the average production budget over time reveals significant trends in movie financing.

![Average Movie Budget Over Time](./images/average_movie_budget_over_time.png)

### Distribution of IMDB Ratings

The distribution of IMDB ratings helps understand the overall quality and reception of movies.

![Distribution of IMDB Ratings](./images/distribution_of_imdb_ratings.png)

### Box Plot of Domestic vs Foreign Gross Revenue

A comparison between domestic and foreign gross revenue shows differences in movie performance across regions.

![Box Plot of Domestic vs Foreign Gross Revenue](./images/box_plot_domestic_foreign_gross.png)

### Bar Plot of Average Rating by Genre

Examining the average ratings by genre provides insights into which genres are most appreciated by audiences.

![Bar Plot of Average Rating by Genre](./images/bar_plot_average_rating_by_genre.png)

### Bar Plot of Top 10 Movie Genres

Identifying the top 10 movie genres helps understand audience preferences and market trends.

![Bar Plot of Top 10 Movie Genres](./images/bar_plot_top_10_movie_genres.png)

### Scatter Plot of Production Budget vs Worldwide Gross

A scatter plot of production budgets versus worldwide gross revenue illustrates the relationship between investment and financial return.

![Scatter Plot of Production Budget vs Worldwide Gross](./images/scatter_plot_budget_vs_gross.png)

## Conclusions

Based on the analysis, the following recommendations are made to improve decision-making in movie production and marketing:

- **Invest in High-Budget Blockbusters:** Action and Adventure genres with substantial production budgets tend to achieve higher global box office revenues.
- **Focus on Family-Oriented Genres:** Genres such as Animation, Family, and Adventure attract wide audience bases and enhance box office success.
- **Capitalize on Franchises and Sequels:** Movies that are part of well-known franchises or sequels perform exceptionally well at the box office.
- **Develop Global Marketing Strategies:** Target both domestic and international markets to maximize revenue.
- **Optimize Budget Allocations:** Regularly review and optimize production budgets to ensure efficient use of resources.

### Next Steps

Further analyses could provide additional insights to enhance decision-making:

- **Predict Long Stays for Animals:** Use available data to predict animals likely to have long stays at shelters.
- **Model Medical Support Needs:** Predict the need for specialized personnel based on intake condition and sex data.
- **Identify Animals with Undesirable Outcomes:** Target medical support or outreach for animals more likely to have undesirable outcomes.
