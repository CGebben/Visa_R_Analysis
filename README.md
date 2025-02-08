# Visa Analysis with R

## Overview  
This project analyzes Irish visa data using R, focusing on visa grants and refusals across different nationalities and time periods. 
It was developed as the final project for my **Data Programming with R** module at University College Dublin.  

## Features  
- Data **cleaning, validation, and merging** across four datasets.  
- **Visualization of trends** in visa applications, grants, and refusals.  
- **Regional analysis** by linking visa data to United Nations geographical classifications.  
- **Custom R functions** for summarizing and plotting visa trends.  
- **Interactive maps** using the `leaflet` package.  

## Data Sources  
The dataset originates from Ireland’s [Department of Justice Open Data Portal](https://data.gov.ie/organization/department-of-justice), including:  
- Short-term and long-term visa applications **granted** by nationality and year.  
- Short-term and long-term visa applications **refused** by nationality and year.  

## Technologies Used  
- **Programming Language:** R  
- **Libraries:** `ggplot2`, `dplyr`, `tidyverse`, `leaflet`, `readr`, `tidyr`, `lubridate`, `knitr`  
- **Visualization:** Line charts, bar charts, box plots, and interactive maps.  

## Key Analyses  
### **1️⃣ Visa Trends Over Time**  
- Line graphs illustrate how visa grants and refusals fluctuate over time.  
- Data highlights the **impact of COVID-19**, showing a sharp decline in short-term visa grants in 2020-2021.  

### **2️⃣ Regional Trends**  
- Box plots reveal differences in visa grants and refusals **by world region**.  
- Some regions consistently have higher rejection rates than others.  

### **3️⃣ Top 10 Countries by Visa Refusals & Grants**  
- Bar charts rank the **countries with the most refusals and grants**.  
- Countries in **Western Africa and South Asia** had the highest visa refusals.  
- Some countries appear in both the **most granted and most refused** lists, indicating high application volumes.  

### **4️⃣ Interactive Mapping with Leaflet**  
- An interactive map displays visa refusals over time, allowing users to toggle different years.  
- Circle markers represent visa refusals for each country's capital, colored by year.  

## How to Run the Project  
To run this analysis in R:  
1. Install required packages:  
   ```r
   install.packages(c("ggplot2", "dplyr", "tidyverse", "leaflet", "readr", "tidyr", "lubridate", "knitr"))