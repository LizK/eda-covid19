# Code Folder

![cleaning](https://media-exp1.licdn.com/dms/image/C4D12AQHSzRO0liwLPQ/article-inline_image-shrink_1000_1488/0?e=1596067200&v=beta&t=k97-q1B4LZnChhnHqeLGpbFeGKCf6JaBmhVgoxvhHts)


Welcome to the section of this project containing all of the code.

The first section contains information regarding how to clean the COVID-19 datasets.

## Cleaning Process

### Initial Inspection

Upon initial inspection of the data we saw:

1. A lot of missing data (Maggie)
2. Lots of float values (Jean)
3. Negative numbers where there shouldn't be any (Maria)
4. Parse date during import (Matt)
5. Why do we have smokers in the dataset? (Elizabeth)
6. Large range of values in multiple variables (Thushara)

### Initial Actions

Communicate all measures taken with the stakeholders of the project.

1. Created new date variables (Ramon)
2. Filled in the missing values for the age groups with the median value of their respective column (Matt)
3. We filled missing values in the stringency index column with 0 (Jean)
4. Dropped all NaN values for columns with less 5% of values missing (Thushara & Elizabeth)
5. Removed columns with more than 50% missing values (Maggie)
6. Dropped missing values for columns with 15% or less missing values (Maria)
7. Extreme poverty column NaN's where replaced with the median of that same column (Thushara)


## EDA Process

Findings

1. There was a sharp increase in cases between March and the end May.
2. Only South America continues to show an increase in cases in comparison to other continents.
3. Africa and Oceania have the lowest average case reported per day in comparison to North America, Asia, and South America.
4. There appears to be no static difference in the availability of beds by the thousands in each continent and by weekend. The trend changes month over month from low availability in April and May to more available beds in June.
5. Since the pandemic started, the days where the least amount of reported cases occur are Mondays and Thursdays.
