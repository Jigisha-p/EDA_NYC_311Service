# Customer Service Requests Analysis

This is a data analysis of service request (311) calls from New York City. Various data wrangling techniques have been employed to comprehend the data patterns and create visualizations highlighting the primary categories of complaints.


### Steps:

1. Understand the dataset:
  - Identify the shape of the dataset
  - Identify variables with null values
2. Perform basic data exploratory analysis:
- Utilize missing value treatment
- Analyze the date column and remove the entries if it has an incorrect timeline
- Draw a frequency plot for city-wise complaints
- Draw scatter and hexbin plots for complaint concentration across Brooklyn
3. Find major types of complaints:
- Plot a bar graph of count vs. complaint types
- Find the top 10 types of complaints
- Display the types of complaints in each city in a separate dataset
4. Visualize the major types of complaints in each city
5. Check if the average response time across various types of complaints
6. Identify significant variables by performing a statistical analysis using p-values and chi-square values

### Setup and Installation:
```bash
pip install --upgrade pip
pip install -r requirements.txt
pip list
```
