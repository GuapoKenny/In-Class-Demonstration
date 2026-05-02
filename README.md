# In-Class-Demonstration
# NFL Player Salaries Project

## Project Overview

This project analyzes NFL player salaries by position and year. The main goal is to understand how much average salaries differ across positions and whether higher market-value positions, such as quarterbacks and linemen, receive higher average salaries.

Instead of only looking at the highest-paid individual players, this project treats the NFL as a labor market. In this labor market, teams pay different amounts based on the value, scarcity, and importance of each position.

## Project Motivation

NFL salaries are not just about sports. They also show how compensation works in a competitive labor market. Some positions may be harder to replace, more valuable to team success, or more expensive because of demand.

This project helps answer a broader economic question: are salary differences mostly explained by position and changes over time?

## Research Questions

1. How much do average NFL salaries differ by player position?
2. Do positions with higher market value, like quarterbacks or linemen, receive higher average salaries?
3. How have salary patterns changed over time across key positions?
4. Which NFL positions have experienced the largest salary growth over time?

## Data Source

The main dataset used in this project is an NFL salary dataset. The dataset includes salary values by position and year.

The years included in the dataset are 2011–2018.

## Main Variables

| Variable | Description |
|---|---|
| year | The year of the salary observation |
| position | The NFL player position |
| salary | The salary or contract value for that position |

## Tools Used

This project was completed using:

- R
- RStudio
- tidyverse
- readxl
- janitor
- scales
- ggplot2

## Data Cleaning Process

The dataset was first loaded into R from an Excel file. Column names were cleaned using the `clean_names()` function from the janitor package. The dataset was then reshaped from wide format into long format using `pivot_longer()`.

This made the data easier to analyze because each row contained a year, position, and salary value.

## Analysis Steps

The analysis included:

1. Loading and cleaning the NFL salary dataset.
2. Reshaping the data into long format.
3. Calculating average and median salary by position.
4. Comparing high market-value positions to other positions.
5. Creating salary trend graphs over time.
6. Calculating salary growth by position.

## Figures and Results

### Figure 1: Average NFL Salary by Position

This chart shows the average salary for each NFL position. It helps answer the first research question by showing which positions have the highest and lowest average salaries.

**Main takeaway:** Average salaries differ across NFL positions. Some positions, especially linemen, quarterbacks, and linebackers, appear to have higher average salaries than others.

![Average Salary by Position](average_salary_by_position.png)

### Figure 2: High Market Value Positions

This chart compares high market-value positions, such as quarterbacks, offensive linemen, and defensive linemen, to other positions.

**Main takeaway:** Higher market-value positions tend to have higher average salaries, which supports the idea that salary differences are connected to position value and scarcity.

![High Market Value Positions](high_market_value_positions.png)

### Figure 3: Salary Trends Over Time

This line chart shows how average salaries changed over time by position.

**Main takeaway:** Salary patterns changed between 2011 and 2018. Some positions experienced stronger salary growth than others.

![Salary Trends Over Time](salary_trends_over_time.png)

### Figure 4: Salary Trends Across Key Positions

This chart focuses on selected key positions, including quarterback, offensive lineman, defensive lineman, wide receiver, running back, and cornerback.

**Main takeaway:** Looking only at key positions makes it easier to compare salary growth patterns over time.

![Key Position Salary Trends](key_position_salary_trends.png)

### Figure 5: Percent Salary Growth by Position

This chart shows which positions experienced the largest percentage growth in salary over the years included in the dataset.

**Main takeaway:** Some positions grew faster than others, suggesting that the market value of certain NFL roles changed over time.

![Percent Salary Growth](percent_salary_growth.png)

## Main Results

The results show that NFL salaries are not equal across positions. Some positions receive higher average salaries, which may be because those positions are more valuable, harder to replace, or more important to team success.

The results also show that salary patterns changed over time. Certain positions experienced more salary growth than others between 2011 and 2018.

Overall, the project supports the idea that NFL salaries reflect labor market differences across position, year, and market value.

## Files in This Repository

| File | Description |
|---|---|
| README.md | Explains the project motivation, research questions, data, methods, figures, and results |
| nfl_salary.xlsx | Main salary dataset used for the project |
| nfl_salary_analysis.R | R script used to clean the data, calculate summary statistics, and create graphs |
| average_salary_by_position.png | Bar chart showing average salary by position |
| high_market_value_positions.png | Bar chart highlighting quarterbacks and linemen |
| salary_trends_over_time.png | Line chart showing salary trends over time |
| key_position_salary_trends.png | Line chart for selected key positions |
| percent_salary_growth.png | Bar chart showing percent salary growth by position |
| NFL_Salary_Project_Proposal.pptx | PowerPoint presentation summarizing the project |

## Conclusion

This project shows that NFL salary differences are strongly connected to player position and year. Higher-value positions tend to receive higher salaries, and some positions experienced stronger salary growth over time.

The NFL can be understood as a labor market where pay reflects demand, scarcity, and the value of different skills.
