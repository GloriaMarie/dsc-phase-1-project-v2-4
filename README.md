# Project Overview

Microsoft is a global tech leader looking to diversify its business portfolio by entering the film and content creation industry. This move aligns with Microsoft's broader goals of increasing revenue and leveraging its existing infrastructure and expertise to compete in the global entertainment industry.

## Business Domain

The film industry encompasses film production and distribution, offering various genres and distribution channels. Traditional distribution models have shifted with the rise of streaming platforms, transforming the industry. Technology has played a significant role, introducing high-resolution cameras, editing tools, immersive storytelling through virtual and augmented reality, and data-driven content recommendations.

## Business Problem

Microsoft faces challenges entering this market due to competition from established studios, the need for substantial investments in talent and marketing, licensing and regulatory requirements, and staying up-to-date with trends and user preferences.

## Objectives

1. Compare the performance of different studios in terms of domestic and foreign gross.
2. Analyze the relationship between production budgets and domestic/worldwide gross.
3. Investigate whether movies with more votes tend to have higher ratings (popularity vs. rating).

## Data Understanding

The project utilizes three datasets: `bom.movie_gross.csv`, `im.db`, and `tn.movie_budgets.csv` to gather relevant information.

## Data Cleaning

### Objective 1
- Cleaned the `bom.movie_gross.csv` data, converting the `foreign_gross` column to a numeric type and handling missing values by imputing with the mean.

### Objective 2
- Cleaned the budget dataset, removing special characters and converting columns to numeric types.

### Objective 3
- Cleaned the dataset containing the number of votes and average ratings, removing outliers.

## Data Analysis

Different exploratory data analysis techniques were applied to achieve clean and workable data for each objective.

### Objective 1
- Analyzed the relationship between domestic and foreign gross for top studios.
- Observed variations in domestic gross among top studios.
- Noted that foreign gross is significantly higher than domestic gross.

### Objective 2
- Investigated the correlation between production budgets and domestic/worldwide gross.
- Explored return on investment (ROI) for each movie.
- Explored ROI distribution through histograms.

### Objective 3
- Explored the correlation between the number of votes and average ratings.
- Visualized this relationship using a scatter plot.

## Recommendations

1. Focus on user engagement strategies, as ratings are influenced by various factors beyond popularity.
2. Be cautious about correlating higher budgets with higher ROI; further market research is essential.
3. Consider genre preferences when entering the industry, as different studios are known for different genres.


