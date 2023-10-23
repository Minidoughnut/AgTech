## Introduction
Did you know that as of November 2022, the world's population reached a staggering 8.0 billion? The United Nations predicts that this number will surge by nearly 2 billion within the next three decades, hitting 9.7 billion by 2050 and potentially peaking at 10.4 billion by the mid-2080s. This dramatic population growth presents a daunting challenge – global food security. 
In a world grappling with growing populations and pressing environmental concerns, this project endeavors to bridge the gap between food security and sustainability.

## Problem Statement
Approximately 345 million individuals already grapple with hunger, and the situation could worsen.
Against the backdrop of diminishing farmlands, it's imperative that farmers, governments, and stakeholders explore innovative strategies to increase food production without exacerbating environmental degradation and the climate crisis. The key lies in harnessing insights from historical agricultural data to implement sustainable practices.
The Prairie provinces of Canada are renowned for grain farming and exports. Our project delves into an analysis of crop yields in the rural municipalities of Saskatchewan and Manitoba. By examining spatial patterns and historical data, we aim to provide actionable findings that suggest optimal crop rotation strategies for enhancing agricultural productivity.

## Data Collection and Preprocessing
The primary sources of data for this project included yield data in Excel and CSV formats for common grains, along with shapefiles containing metadata for the rural municipalities in Saskatchewan and Manitoba. These datasets were ethically sourced from the governments of Saskatchewan and Manitoba.
Using Python and the necessary libraries, several critical preprocessing steps were executed to ensure the integrity and consistency of the data:
*	The datasets underwent a thorough cleaning process to eliminate outdated records and remove missing or erroneous values.
*	Data transformation was employed to ensure uniformity and ease of analysis. This included unit conversions, such as changing measurements to bushels per acre.
*	To create a cohesive dataset, columns from disparate sources were standardized and harmonized. This facilitated the integration of crop yield data with their corresponding geographic locations using shapefiles.
Here's a glimpse of the data and some preliminary visualizations to provide insight into our dataset:
### Raw Yield Data:
![image](https://github.com/Minidoughnut/AgTech/assets/104665188/ce1b2b01-ea15-46ed-8d7a-353bd1f560b8)
A snapshot of raw yield data for Saskatchewan

 ![image](https://github.com/Minidoughnut/AgTech/assets/104665188/61743d43-e2e5-424d-a900-bcb1480e7b27)
A snapshot of raw yield data for Manitoba.
 
### Transformed Data:
 ![image](https://github.com/Minidoughnut/AgTech/assets/104665188/ffd9784c-3902-4331-b9f6-5ba72037b2f4)
 ![image](https://github.com/Minidoughnut/AgTech/assets/104665188/2a17482e-b763-43e4-81fc-589b570a25be)

A snapshot of standardized and merged yield data for Saskatchewan and Manitoba.

## Exploratory Data Analysis (EDA)
Initial data visualization using a bar chart on the dataset, revealed the presence of a substantial 95,891 missing values. To make the dataset more relevant and focused, we narrowed our analysis to the past decade, spanning from 2002 to 2022. This reduced the count of missing values to 19,060, offering a more current and representative dataset for our investigation.
Subsequently, these null values were thoughtfully and systematically removed.  This rigorous data preprocessing step allowed us to sharpen our focus on the essential trends, patterns, and relationships that emerged during our analysis, ensuring that our findings are rooted in robust and up-to-date information

