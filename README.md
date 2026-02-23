# Justice John Paul Stevens — Sentiment Analysis

## Overview
This project performs a custom sentiment analysis of Justice John Paul 
Stevens' authored concurring and dissenting opinions on the U.S. Supreme Court between 1976 to 1980.
Opinions are scored across six emotional categories: Belonging, Liberty, 
Empathy, Control, Contentment, and Discontentment. Analysis aims to model some of the framework 
established by Sears, Lapidus and Cozzens (1978) "Content Analysis of Mark Twain's Novels and Letters as a Biographical Method", to understand
the correlation between emotional experience and judicial decison making in a political psychology study.

## Data
- Source: Supreme Court opinion texts
- Coverage: Stevens' tenure on the court pre-divorce, mid-divorce and post-divorce (1976–1980)
- Format: CSV with columns for case name, opinion type, year, and opinion text

## Requirements
The following R packages are required:
- tidyverse
- tidytext
- stringr
- ggplot2
- scales
- DescTools
- prettydoc

## How to Run
1. Clone this repository
2. Open `Stevens-Sentiment-Analysis.Rmd` in RStudio
3. Place `stevensdata.csv` in the same folder
4. Click Knit to generate the HTML report

## Key Findings
- Summary of dominant emotions reflected in the authored opinions that occurred across the examined time periods
- Emotional distribution and changes over time
- Comparison of concurring vs. dissenting opinion emotional profiles
- Temporal trends in emotional language across time 

## Author
Gianna DiBartolo
Rutgers University
