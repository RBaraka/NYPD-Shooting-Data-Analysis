# NYPD Shooting Incident Data Report 

This project explores historic NYC shooting data to uncover actionable patterns in gun violence.

## Files
- [Shooting-in-NYPD.Rmd](Shooting-in-NYPD.Rmd) - Full analysis (rmd)
- [Shooting-NYPD-Data-Analysis.pptx](Shooting_NYPD_Data_Analysis.pptx) Final presentation (ppt)
- [Shooting-in-NYPD.html](Shooting-in-NYPD.html): Knitted report (html)

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
- [NYPD Shooting Incident Data (Historic)](https://catalog.data.gov/dataset/nypd-shooting-incident-data-historic)

## Presentation
- The presentation video walks through the findings in 10 minutes.
- [Click to watch the 10-minute video](https://drive.google.com/file/d/1TN8JhEs645gLDbcmJjAwyRZK27k9DjAc/view?usp=sharing)

## Instructions
- To reproduce the report:
	1.	Clone the repo
	2.	Open Shooting-in-NYPD.Rmd in RStudio
	3.	Install any missing packages
	4.	Knit the document to HTML
