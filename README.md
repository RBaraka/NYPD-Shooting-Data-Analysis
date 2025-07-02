# NYPD Shooting Incident Data Report 

This project explores historic NYC shooting data to uncover actionable patterns in gun violence.

## Files
- `Shooting-in-NYPD.Rmd`: Full analysis (RMarkdown)
- `Shooting-NYPD-Data-Analysis.pptx`: Final presentation
- `output/final_report.html`: Knitted report
- `data/`: Folder for raw or cleaned data

## Insights
1. Most victims are men aged 18–44
2. Incidents spike on weekends
3. Summer months show higher shooting rates

## Libraries Used
Make sure these are installed before knitting:
```r
library(tidyverse)
library(lubridate)
library(forecast)
library(ggplot2)
```
## Data Source
- NYPD Shooting Incident Data (Historic)

## Presentation
- The presentation video walks through the findings in 10 minutes.

## Instructions
- To reproduce the report:
	1.	Clone the repo
	2.	Open Shooting-in-NYPD.Rmd in RStudio
	3.	Install any missing packages
	4.	Knit the document to HTML
