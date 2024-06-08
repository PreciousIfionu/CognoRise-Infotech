# UNEMPLOYMENT RATE IN INDIA 
### (2019 - 2020)

### Table of Content

[Introduction](#introduction)

[Data Source](#data-source)

[Tools Used](#tools-used)

[Columns in the Dataset](#columns-in-the-dataset)

[Data Cleaning and Manipulation](#data-cleaning-and-manipulation)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Summary of Data Analysis](#summary-of-data-analysis)

[Key Visualizations and Findings](#key-visualizations-and-findings)

[Recommendations](#recommendations)


- ![Screenshot (150)](https://github.com/PreciousIfionu/CognoRise-Infotech/assets/166953936/d55308c4-185a-4588-9a16-0491fa8421b2)

## Introduction

This project focuses on analyzing the unemployment rate in India during the period from 2019 to 2020. The primary objective is to uncover trends, identify regional disparities, and provide insights that can guide policy decisions and interventions.

## Data Source
The dataset used for this analysis was sourced from the National Sample Survey Office (NSSO), India. It includes comprehensive data on the unemployment rate, employment rate, labor participation rate, and demographic details across various regions in India.

## Columns in the Dataset:
- Regions: Geographical areas within India.

- Dates: Monthly data points.

- Frequency: Monthly.

- Estimated Unemployment Rate (%): Percentage of unemployed individuals.

- Estimated Employment Rate: Absolute number of employed individuals.

- Estimated Labor Participation Rate (%): Percentage of the labor force that is actively participating in the job market.

- Area: Classification into rural and urban regions.
  

## Tools Used

 - Microsoft Excel: Utilized for initial data cleaning and manipulation tasks.
 - Microsoft Power BI: Employed for data visualization and dashboard creation.

## Data Cleaning and Manipulation

1. ### Handling Missing Values:

- Identification: Identified rows with missing dates and values.
- Imputation: Filled in missing dates to maintain chronological consistency using interpolation techniques where necessary.
- Validation: Ensured no critical data was omitted in the process.
  

2. ### Correcting Data Types:

- Date Formatting: Converted text-formatted dates into standard date formats to facilitate time series analysis.
- Percentage Calculations: Ensured tha
  
  
3. ### Transformations:

- Percentage Calculations: Calculated employment rates and labor participation rates as percentages for consistency.
- Standardization: Standardized all numerical values to ensure uniformity across the dataset.
  
  
4. ### Removing Duplicates:

- Verification: Checked for and removed any duplicate records to ensure data integrity.

5. ### Data Verification:

- Cross-Validation: Cross-checked the cleaned dataset against the original data source to ensure accuracy and completeness.

  
## Summary of Data Analysis

The analysis aimed to provide a detailed understanding of the unemployment trends in India. By examining how the unemployment rate varied over time and across different regions, the study sought to identify key patterns and relationships.

## Exploratory Data Analysis
### Key Questions Addressed:

- Temporal Trends: How did the unemployment rate change over time?
- Regional Disparities: Which regions experienced the highest and lowest unemployment rates?
- Labor Participation: What is the relationship between the unemployment rate and the labor participation rate?


## Key Visualizations and Findings

1. ## Labor Participation Rate by Year
   ### Visualization: Line Chart

## Analysis:
The labor participation rate fluctuated significantly between July 2019 and May 2020. The peak was observed around October 2019, indicating a high engagement in the labor market. However, the rate experienced a downward trend entering 2020, likely due to the economic disruptions caused by the COVID-19 pandemic. The overall participation rate stabilized around mid-2020 but remained lower compared to the peak.





![Screenshot (208)](https://github.com/PreciousIfionu/CognoRise-Infotech/assets/166953936/b808a9f6-97fb-44e7-a3d0-23938c44a8ca)





2. ## Unemployment Rate by Year
   ### Visualization: Line Chart

## Analysis:
The unemployment rate exhibited a sharp increase at the beginning of 2020, correlating with the economic impact of COVID-19. This spike reflects the significant job losses and reduction in economic activities during the early months of the pandemic. A gradual decline is observed post- February 2020, suggesting a slow recovery in employment as restrictions eased and economic activities resumed. However, the unemployement rate picked up again post April which was as a result of the covid 19 safety regulations





![Screenshot (209)](https://github.com/PreciousIfionu/CognoRise-Infotech/assets/166953936/ad477b78-4f21-4328-bf8a-e6e8c87658a7)







3. ## Employment and Labor Participation by Date
### Visualization: Combined Bar and Line Chart

## Analysis:
This visualization integrates the total estimated number of employed individuals (represented by bars) with the average labor participation rate (depicted by a line). Notably, there is a significant decline in labor participation around November 2019, attributed to the onset of the COVID-19 pandemic, which led to widespread workforce withdrawals. Correspondingly, the employment rate experienced a sharp decrease post-November, followed by a brief recovery and another decline in early 2020. However, in June 2020, there was a slight uptick in both the employment rate and labor participation rate. This pattern highlights a strong correlation between employment levels and labor market engagement, underscoring the pandemic's profound impact on labor market dynamics.



![Screenshot (210)](https://github.com/PreciousIfionu/CognoRise-Infotech/assets/166953936/92b73445-7930-4e3f-9b64-d02b5f2af1a7)




4. ## Unemployment Rate by Area
### Visualization: Pie Chart

## Analysis :

The distribution of unemployment rates between rural and urban areas revealed that urban areas experienced higher unemployment rates compared to rural areas. This can be attributed to the higher concentration of service and industrial jobs in urban areas, which were more severely affected by lockdown measures and social distancing norms. Rural areas, with a greater reliance on agriculture and less dense populations, were comparatively less impacted.


![Screenshot (212)](https://github.com/PreciousIfionu/CognoRise-Infotech/assets/166953936/378fe2c9-1729-4e13-8dbc-8bd6b1164ec9)


5. ## Unemployment Rate by Region
   ### Visualization: Bar Chart
   ### Insight: 
Significant regional disparities in unemployment rates were observed. Regions such as Tripura, Haryana, Jharkhand, Bihar showed higher unemployment rates, likely due to their large urban populations and reliance on industries heavily impacted by the pandemic. In contrast, states like Puducherry, Kerala, Tamil Nadu had relatively lower unemployment rates, potentially due to their higher rural populations and greater engagement in agriculture, which was less affected by the pandemic.


![Screenshot (213)](https://github.com/PreciousIfionu/CognoRise-Infotech/assets/166953936/da6f693c-6630-4cd0-a5f8-9a239b986c29)


6. ## Estimated Employed by Region
   ### Visualization: TreeMap
   ### Insight:

   The treemap visualization displays the average number of estimated employed individuals by region in India. Each block represents a region, with the size of the block proportional to the number of employed individuals.Uttar Pradesh has the largest block, indicating it has the highest number of employed individuals (Average of 28.09M people employed) reason being that Uttar Pradesh is the most populous state in India, which correlates with a higher number of employed individuals. Bihar has a significant number of employed individuals, being the second largest block with an average of 12.37 million individuals employed.Bihar has a large population, which contributes to its high employment numbers despite lower economic development compared to some other states.

![Screenshot (214)](https://github.com/PreciousIfionu/CognoRise-Infotech/assets/166953936/5b1b42b0-e1fb-4f8f-89d2-434acb9c2357)


## Recommendations
Based on the analysis, several recommendations are proposed to address the unemployment challenges identified:

### Targeted Policy Interventions: Implement policies aimed at regions with the highest unemployment rates to stimulate job creation and economic activity.

### Support for Rural Areas: Develop programs to increase employment opportunities in rural areas to balance the urban-rural unemployment disparity.

### Ongoing Monitoring: Establish a system for continuous monitoring and analysis of unemployment trends to quickly identify and respond to emerging issues.

## Conclusion

This project provided valuable insights into the unemployment trends in India from 2019 to 2020. By utilizing Excel for data cleaning and Power BI for visualization, the analysis highlighted critical areas needing intervention. The findings from this study can help guide policymakers and stakeholders in making informed decisions to improve employment rates and labor participation across India.

