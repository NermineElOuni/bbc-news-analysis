# BBC News Articles Analysis

## Overview
Analysis of 35,000+ BBC News articles 
published between March 2022 and July 2024,
exploring geographical distributions and 
topical trends over time.

Completed as part of MSc Data Science and 
Business Analytics, University of Plymouth,
2025.

## Dataset
- 35,000+ BBC News articles
- Variables: title, publication date,
  guid, url, description 
  
- Source: BBC News Website

## Methods & Tools
**Language:** R

**Libraries:**
- tidyverse (data manipulation)
- dplyr (data wrangling)
- ggplot2 (visualisation)
- lubridate (date parsing)
- tm (text cleaning)
- stringi (regex pattern matching)
- ggtext (text formatting in plots)

**Techniques:**
- Data cleaning and preprocessing
- Duplicate detection and removal
- Missing value handling
- Text cleaning and standardisation
- Regex pattern matching for 
  geographical classification
- Time series analysis
- Interactive map visualisation
- Faceted visualisations

## Data Cleaning Steps
1. Parsed and standardised date formats
2. Identified and removed duplicate 
   articles via guid deduplication
3. Handled missing values
4. Cleaned text fields (whitespace, 
   numbers, special characters)
5. Filtered incomplete time periods
6. Classified articles into geographical 
   regions using regex pattern matching

## Key Findings
- UK and US are the most covered 
  regions in BBC News articles
- NO pollution is higher in PLYR than 
  PLYM monitoring sites
- NO₂ concentrations relatively stable 
  across both Plymouth locations

## How to Run
1. Clone or download this repository
2. Place the CSV data files in the 
   same folder as the .Rmd file
3. Open the .Rmd file in RStudio
4. Install required packages:
   install.packages(c("tidyverse", "tm", 
   "stringi", "ggtext", "lubridate",
   "wordcloud", "wordcloud2"))
5. Click "Knit" to run the full analysis
