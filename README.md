# Financial Time Series Visualization Tutorial

## Overview
This tutorial demonstrates how to visualize and analyze financial time series data in R, with a focus on checking normality assumptions and identifying patterns in stock returns. It's designed for students and practitioners in finance who want to develop their data exploration skills.

## Prerequisites
- Basic knowledge of R programming
- Understanding of basic financial concepts (returns, time series)

## Required R Packages
```r
library(tidyverse)   # Data manipulation and visualization
library(tidyquant)   # Financial data retrieval and analysis
library(fpp2)        # Forecasting functions
library(tsfe)        # Class datasets
library(ggpmisc)     # Advanced plotting features
library(DT)          # Interactive tables
```

## Topics Covered
1. Time series object creation and manipulation

2. Visualization techniques:
   - Time plots
   - Seasonal plots
   - Subseries plots

3. Normality testing:
   - Histograms with normal distribution overlay
   - QQ plots
   - Shapiro-Wilk test

4. Pattern detection:
   - Autocorrelation functions (ACF)
   - Lag plots

## Usage
1. Open the `.qmd` file in Posit Cloud
2. Install required packages if needed
3. Execute the code chunks sequentially
4. Complete the exercises at the end to practice with different stocks

## Example Data
The tutorial uses Glencore (GLEN.L) stock data as an example, but you can easily modify the code to analyze other stocks by changing the ticker symbol.

## Interactive Features
- Code folding enabled
- Table of contents
- Exercise sections for practice
- Detailed interpretations of each visualization

## Contributing
Feel free to submit issues and enhancement requests!

## License
MIT