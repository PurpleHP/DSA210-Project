# DSA210-Project: Step-Count Analysis

## Motivation
As a Junior CS student I don't know what grass looks like. So in this project I'm aiming to understand my behaviours.
This project is an attempt to change that. By analyzing my step count data, I aim to understand my behavior and identify patterns in my physical activity. 

Some key questions I want to explore include:
- What motivates me to walk more?
- Which days am I more active?
- Is school the main driver of my activity levels?
- How do my step counts differ between weekdays and weekends?

Through this analysis, I hope to gain insights into my lifestyle

## Data Source
The dataset consists of step count records collected from my Huawei device (from Huawei Health App between 07/08/2019 to 15/11/2024). The data was obtained through Huawei’s official data request service, where I manually requested a copy of my personal data. Huawei provided the data in a large zip file containing minute-by-minute step count logs. I processed and combined this data into a daily step count dataset for easier analysis.

### Data Collection Process Step by Step:
1. **Requesting the Data**: I requested my step count data from Huawei via their user data export service.
2. **Data Extraction**: Once the data was received, I extracted the zip file, which contained JSON files organized minute-by-minute.
3. **Data Processing**: Using Python, I processed the JSON files to aggregate step counts on a daily basis. This involved combining step data from multiple files for the same day into a single value representing the total daily step count.
4. **Final Dataset**: The final dataset includes daily step counts from July 2021 to November 2024, formatted as `{date: step_count}`.

## Project Idea
The main objective of this project is to analyze my step count data to uncover patterns, trends, and insights. Specific goals include:
- Understanding my walking behavior over the years.
- Identifying seasonal or temporal trends in step counts.
- Analyzing whether school or other external factors influence my activity levels.
- Comparing activity levels between weekdays and weekends to understand behavioral differences.

![image](https://github.com/user-attachments/assets/76c72f54-d87c-485b-a0e6-b88ab931d239)
