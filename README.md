MLBAttendanceProject - Data and R code for analyzing professional baseball attendance. 
================================

Dependencies (all open source)
--------------------------
- [R](https://www.r-project.org/)
- [RStudio](https://www.rstudio.com/)
- [tidyverse](https://www.tidyverse.org/)
- [sjPlot](https://github.com/strengejacke/sjPlot/)

Data Input
--------------------------
The data is all publicly available from baseball-reference.com, the Bureau of Labor Statistics, the U.S. Census Bureau, StatCan, and ballparksofbaseball.com and is expected to be inserted into the `data/` folder. 

Data Wrangling
--------------------------
The data cleaning, transforming, and merging functionality is located in `CleanMergeAndTransformData.Rmd` and will output to `data/attendanceTicketPriceWAR.csv`.

Data Models and Visualizations
--------------------------
The modeling is computed and visualizations rendered in `MLBAttendanceModels.Rmd` and will use `data/attendanceTicketPriceWAR.csv` from the data wrangling stage.

Data Output
--------------------------
The models will be output within [RStudio](https://www.rstudio.com/) as [sjPlot](https://github.com/strengejacke/sjPlot/) tables. The summary statistics will be output in `data/summaryStats.csv'. 

