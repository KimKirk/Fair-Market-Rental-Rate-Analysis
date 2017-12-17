# HADS_Fair-Market-Rental-Rate

- All files are self-contained analysis reports that include necessary variables. 

- Many businesses still use Excel as a primary "database"/data storage device; to accomodate this, all files are Excel based and analysis was run using Excel. 

- Inferential data analysis was to determine if the 2008 mortgage crisis had an effect on fair market rent (FMR) monthly rate. Hypothesis tested: "did the 2008 mortgage/housing crisis have an effect on fair market monthly rental rates (FMR) over various years? A two-tailed difference in means paired t-Test was run to determine statisical significance between group means; results are listed in the "Summary Report" worksheet.

## Processing Instructions:
- Use Excel or application that can open .xlsx files to view the analysis report. 
- Each worksheet is labeled to include "Summary Report", "Descriptive Statistics", "Graphs", and "Tests".

## Steps to Transformation:
### Data was tidied by: 
- All data points for VALUE variable less than $1000.00 were removed per project instructions.
- All NULL values were removed. Missing values were missing because the original data source has odd-numbered years in 1985-2009 and "selected only records representing completed interviews for occupied and vacant units, excluding usual residence elsewhere (URE) and noninterview records." per HADS documentation file. https://www.huduser.gov/portal/datasets/hads/HADS_doc.pdf

1. Dataset was downloaded from host website: https://www.huduser.gov/portal/datasets/hads/hads.html
2. CONTROL variable and FMR variable over five years was used for analysis.
   - FMR is numeric continuous, normally distributed.
   - CONTROL is categorical, nominal.
3. FMR was determined to be the dependent variable, CONTROL was determined to be the independent variable.
4. FMR data across five years was merged into one data set for each CONTROL housing unit.
5. New variables created include:
   - FMR 2005
   - FMR 2007
   - FMR 2009
   - FMR 2011
   - FMR 2013
4. Worksheets were created to hold four categories for the analysis: 
   - Summary Report identifies and answers the business question/what was measured
   - Descriptive Statistics identifies and calculates descriptive statistics
   - Graphs displays histograms and boxplots
   - Tests holds results for statistical tests

