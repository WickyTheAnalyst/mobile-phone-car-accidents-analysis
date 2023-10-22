# Mobile Phones and U.S. Car Accidents - Inferential Analysis

**Date:** October 12, 2023

**Prepared by:** [Waqas Ahmad]

## Table of Contents
- **Abstract**
- **Introduction**
- **Data Collection**
- **Data Preprocessing**
- **Exploratory Data Analysis (EDA)**
  - *Part 1: Car Accident Trends*
  - *Part 2: Smartphone Usage Trends*
- **Hypothesis Testing**
  - *ANOVA (Analysis of Variance)*
  - *Tukey's Honestly Significant Difference (HSD) Test*
  - *Regression Discontinuity (RD) Analysis*
- **Conclusion**
- **Recommendations**
- **Acknowledgments**
- **References**

## Abstract

This project explores the relationship between car accident trends and smartphone adoption in the United States. It analyzes crash data over the years, focusing on the period surrounding the introduction of smartphones in 2011. The project employs statistical methods, visualizations, and hypothesis testing to evaluate the impact of smartphone adoption on accident rates.

## Introduction

The rapid proliferation of smartphones in the last two decades has led to concerns about their potential impact on road safety. This project seeks to understand whether the introduction of smartphones in 2011 corresponds with significant changes in car accident rates. The analysis also considers seasonal variations and explores factors contributing to accident trends.

## Data Collection

Two primary datasets were used:

1. **Car Accident Data:** This dataset includes car accident statistics from 2001 to 2021, with monthly data on crash rates, categorized by month, season, and type of crash.

2. **Smartphone Adoption Data:** This dataset tracks the percentage of American adults using smartphones over time, starting from the early 2010s.

## Data Preprocessing

Data preprocessing included cleaning, aggregation, and merging of the two datasets. Key preprocessing steps involved handling missing values and transforming data into suitable formats for analysis.

## Exploratory Data Analysis (EDA)

**Part 1: Car Accident Trends**

The analysis of car accident data revealed the following trends:

- An overall decreasing trend in accident rates before 2011.
- A noticeable shift around 2011, but causality is inconclusive.

**Part 2: Smartphone Usage Trends**

Analysis of smartphone usage trends indicated:

- Steady increase in smartphone usage from 2011.
- No clear evidence to attribute the observed accident trend shift solely to smartphone adoption.

## Hypothesis Testing

**ANOVA (Analysis of Variance)**

- Null hypothesis: The season has no impact on crash rates.
- ANOVA results: Statistically significant differences in crash rates among seasons, highlighting a seasonal effect on accidents.

**Tukey's Honestly Significant Difference (HSD) Test**

- Revealed specific pairs of seasons with significantly different crash rates.
- Fall and Winter showed different rates compared to Spring and Summer.

**Regression Discontinuity (RD) Analysis**

- Investigated the impact of smartphone adoption on crash rates before and after 2011.
- Regression analysis and RD plot did not show a statistically significant increase in accidents linked to smartphone adoption.

## Conclusion

The project's key findings and insights can be summarized as follows:

- Seasonal patterns play a significant role in car accident rates, with higher rates in Fall and Winter.
- The introduction of smartphones in 2011 does not appear to be the sole driver of the observed shift in accident trends.
- Multiple factors, including weather conditions and societal influences, contribute to changes in accident rates.
- Further comprehensive research is essential to disentangle the complex relationship between smartphone usage and car accidents.

## Recommendations

- Continue monitoring and research: Given the dynamic nature of smartphone technology, ongoing analysis is crucial.
- Expand the dataset: Inclusion of more variables and a broader dataset can lead to a better understanding of the relationship between smartphone adoption and accident rates.

## Acknowledgments

We would like to acknowledge the sources of the datasets used in this project, without which this analysis would not have been possible.

## References

This analysis uses publicly available data collected by the National Highway Traffic Safety Administration (NHTSA) and the Pew Research Center. 
#### Data Sources:
- [National Highway Traffic Safety Administration (NHTSA) - U.S. Car Accident Data](https://cdan.nhtsa.gov/query)
- [Pew Research - U.S. Cellphone and Smartphone Ownership Surveys](https://www.pewresearch.org/internet/fact-sheet/mobile/)

