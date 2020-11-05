# Kickstarter-Analysis
## by Julian Gomez
First project for the data scientist nanodegree

## Dataset

The dataset for this project consits of Kickstarter projects from 2009 to 2017. This dataset is available in Kaggle [here](https://www.kaggle.com/kemical/kickstarter-projects). All of the records are individual projects ranging from entertainment, technology, and architecture with indication on whether they came to life or not. Since I am using an app that I found on Kickstarter, I found this dataset interesting to explore in this analysis.

The variables in the dataset include:
- Project ID
- Project name
- Main category
- Secondary category
- project launch date
- project deadline
- currency
- country
- goal amount (in original currency and US dollars)
- pledged amount (in original currency and US dollars)
- number of backers

Libraries used:
- Seaborn
- Pandas
- Datetime
- MatplotLib

## Questions to Explore

1- Which project categories are more likely to succeed?    

2- What is the association between project outcome and fundraising goal?      

3- Which categories are the most popular among backers and, among them, which subcategories tend to exceed or fall behind their goals?        

## Summary of Findings

- The main categories with the highest success probability are dance, theater, and comics projects, even though they rank among the least frequent categories. 

- Project goal plays a fundamental role in project success. Every year, goal amounts vary substantially less on successful projects than unsuccessful ones. This showed that every creator must set a goal that makes backers confident about their success.

- For the most populat project categories, their subcategories fall behind or exceed their goals, which shows how some projects subcategories perform financially.

## Acknowledgement
- Kaggle for the dataset
- Kickstarter website for additional information
