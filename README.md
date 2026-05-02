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

<img width="1290" height="858" alt="Average Salary Yellow" src="https://github.com/user-attachments/assets/f605dbc7-74a5-4140-9014-4cb10648e282" />



### Figure 2: High Market Value Positions

This chart compares high market-value positions, such as quarterbacks, offensive linemen, and defensive linemen, to other positions.

**Main takeaway:** Higher market-value positions tend to have higher average salaries, which supports the idea that salary differences are connected to position value and scarcity.

<img width="1290" height="858" alt="Average Position" src="https://github.com/user-attachments/assets/68341f1f-a9e5-4d2e-91f0-f41ba38f8703" />


### Figure 3: Salary Trends Over Time

This line chart shows how average salaries changed over time by position.

**Main takeaway:** Salary patterns changed between 2011 and 2018. Some positions experienced stronger salary growth than others.

<img width="1290" height="858" alt="Salary Trends" src="https://github.com/user-attachments/assets/0455a6b3-c675-48e2-b6a8-b3554262dc40" />


### Figure 4: Salary Trends Across Key Positions

This chart focuses on selected key positions, including quarterback, offensive lineman, defensive lineman, wide receiver, running back, and cornerback.

**Main takeaway:** Looking only at key positions makes it easier to compare salary growth patterns over time.

<img width="1290" height="858" alt="Key Positions" src="https://github.com/user-attachments/assets/414adf39-262f-4760-b2eb-15b7479f6318" />


### Figure 5: Percent Salary Growth by Position

This chart shows which positions experienced the largest percentage growth in salary over the years included in the dataset.

**Main takeaway:** Some positions grew faster than others, suggesting that the market value of certain NFL roles changed over time.

<img width="1290" height="858" alt="Percent Growth" src="https://github.com/user-attachments/assets/cdf7f54c-3db1-4261-93db-ec5246b9f615" />


## Main Results

The results show that NFL salaries are not equal across positions. Some positions receive higher average salaries, which may be because those positions are more valuable, harder to replace, or more important to team success.

The results also show that salary patterns changed over time. Certain positions experienced more salary growth than others between 2011 and 2018.

Overall, the project supports the idea that NFL salaries reflect labor market differences across position, year, and market value.

## Files in This Repository

## Conclusion

This project shows that NFL salary differences are strongly connected to player position and year. Higher-value positions tend to receive higher salaries, and some positions experienced stronger salary growth over time.

The NFL can be understood as a labor market where pay reflects demand, scarcity, and the value of different skills.
