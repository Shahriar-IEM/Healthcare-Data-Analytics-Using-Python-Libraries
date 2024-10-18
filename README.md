# Healthcare Data Analytics Using Python Libraries

## Project Overview

This project involves the analysis of a healthcare dataset containing over **1.18 million rows** and **34 columns**, covering various **chronic diseases** and demographic data from different U.S. states over several years. The goal is to uncover trends and insights regarding mortality rates for diseases such as:

- Asthma
- Cancer
- Cardiovascular Disease
- Diabetes
- Chronic Kidney Disease
- Chronic Obstructive Pulmonary Disease (COPD)

The dataset provides a comprehensive view of healthcare data across multiple demographic groups, enabling a detailed analysis of trends over time and across regions.

## Exploratory Data Analysis (EDA)

We conducted several steps of **Exploratory Data Analysis (EDA)** to better understand the structure, characteristics, and patterns within the dataset:

1. **Initial Data Exploration**: 
   - Summarized key statistics (mean, median, etc.), column details, and data types.
   
2. **Handling Missing Data**: 
   - Cleaned the dataset by filling missing values and dropping irrelevant or redundant columns.
   
3. **Visualizing Trends**: 
   - Plotted trends over time, analyzed demographic distributions, and explored geographic variations in disease-related mortality.

## Visualizations

The following visualizations were created to aid in understanding the dataset and uncovering key insights:

- **Mortality Rates for Chronic Diseases Over Time**:  
   A line plot visualizing the trends in mortality rates across different chronic diseases from **2010 to 2020**.

- **Geographical Variations**:  
   Bar plots comparing the mortality rates for chronic diseases across different U.S. states, highlighting regional disparities.

- **Mortality Rates by Gender**:  
   A comparison of mortality rates between **male and female** populations for diseases such as **cancer**.

- **Correlation Matrix**:  
   A heatmap displaying the correlations between the mortality rates of chronic diseases, such as diabetes and cardiovascular disease, to identify any relationships.

## Key Findings

Several important insights were drawn from the analysis:

1. **Increasing Trends**:  
   Mortality rates for chronic diseases like **cancer** and **cardiovascular disease** have shown an upward trend over the years.
   
2. **Geographic Disparities**:  
   Significant differences in mortality rates exist between U.S. states. Some regions exhibit much higher mortality rates for specific diseases, indicating geographic disparities in healthcare outcomes.
   
3. **Gender and Age Impact**:  
   Mortality rates differ markedly by **gender** and **age group**, with **older adults** and **males** generally experiencing higher rates for certain diseases, such as **cardiovascular disease**.

## Technologies Used

The project utilized various Python libraries for data analysis, visualization, and numerical operations:

- **Python**: Core language for data analysis and visualization.
- **pandas**: Data manipulation and exploration.
- **matplotlib & seaborn**: Visualization libraries used to create line plots, bar charts, and heatmaps.
- **NumPy**: Numerical operations and array handling.
