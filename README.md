# project2

## Data Sources
- **Air Quality Data**: Daily measurements of CO, PM2.5, and O3 from the RDU airport monitor (2018–2020).

## Files Included
- `AQ_2018.csv`, `AQ_2019.csv`, `AQ_2020.csv`: Raw air quality data
- `project2.Rmd`: RMarkdown file containing all code and analysis
- `project2.docx`: Knitted Word report with plots and commentary
- `README.md`: This file

## Instructions to Run
1. Clone the repository or download the ZIP file.
2. Open the R project in RStudio.
3. Run `project2.Rmd` to reproduce the analysis.
4. Knit the `.Rmd` file to Word for final submission.
5. Ensure the following R packages are installed:
  - `tidyverse`
- `lubridate`
- `ggplot2`

## Key Functions
- `clean_aq_data()`: Cleans and processes raw pollutant data by:
  - Renaming columns
- Formatting dates
- Removing duplicates
- Averaging multiple daily measurements
- Setting negative values to zero

## Visualizations
- **Plot 1**: Monthly average CO and O3 concentrations (2018–2020), with 95% confidence intervals.
- **Plot 2**: Monthly PM2.5 concentrations by year, highlighting seasonal and annual variation.

## Notes
- 2020 data only includes January–April.
- All negative pollutant values were set to zero.
- Duplicate rows and multiple daily measurements were averaged.
- Code is hidden in the final report for clarity and professionalism.

