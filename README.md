# Overview
The primary objective of this project was to analyze a diverse dataset sourced from TidyTuesday, aiming to understand the key factors influencing early career pays of university graduates. It sought to explore correlations between various university attributes, such as STEM percentages, tuition fees and university types, and their impact on the salaries of graduates in their early careers.

# About the data
The dataset originates from TidyTuesday (https://github.com/rfordatascience/tidytuesday/tree/master/data/2020/2020-03-10) and represents a merging of two primary datasets, tuition_cost.csv and salary_potential.csv. Comprising various university attributes, including early and mid-career pays, in-state and out-of-state tuition fees, university types (public, private, for-profit), and alumni perspectives on making a global impact, this dataset offers a diverse array of information. 

# Hypotheses
1) The initial hypothesis postulates a significant correlation between early career pays and the presence of STEM programs or tuition fees. This posits that higher STEM percentages and higher fees might lead to higher early career pays.

2) Another hypothesis assumes that the combined effect of STEM percentages and tuition fees collectively explains more variability in early career pays than STEM percentages alone. This implies that considering both factors together enhances the understanding of early career pays.

3) The third hypothesis suggests that graduates from private universities exhibit a significantly higher early career pay compared to their counterparts from public universities. This implies an anticipated disparity in salary outcomes based on the type of institution attended.

# Conclusions
Influential Factors: In the linear regression analysis, a positive correlation emerged between higher STEM percentages and increased early career pays. To deepen understanding, a multiple linear regression model was employed. Incorporating out-of-state tuition fees as a predictor significantly enhanced the comprehension of the variability in early career pays.

<img width="705" alt="STEM" src="https://github.com/viviennagy/salary-analysis-in-r/assets/152610692/fd67e0f5-6666-4558-ac18-fdc200550c90">

<img width="712" alt="fees" src="https://github.com/viviennagy/salary-analysis-in-r/assets/152610692/a6759421-e438-4b9a-9cf6-f624589e4259">

University Type Differences: The Wilcoxon rank-sum test, highlighted notable differences in early career pays between graduates of public and private universities. Early career pays were observed to be higher among graduates from private institutions in comparison to those from public universities.

<img width="717" alt="Type" src="https://github.com/viviennagy/salary-analysis-in-r/assets/152610692/4fa95d15-1b73-45fc-87e9-e6a792f0a2a8">


# Overall insights
The analysis underlined the importance of certain university attributes, particularly STEM programs and tuition fees, in influencing early career pays. Moreover, it highlighted the differences in salary outcomes between graduates of public and private universities, providing valuable insights for prospective students in understanding the factors shaping early career salary prospects.

