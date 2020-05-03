# Movies-ETL

To support an automated pipeline, a Python function was prepared to automate the extraction, load, and transformation of data from 3 sources into a final Postgre Table

##
Inputs include a Kaggle Metadata file, Wikipedia JSON, and a Ratings extract

## Assumptions

This pipeline is built upon a number of assumptions that were based upon the initial analysis.  These assumptions include:

1 All files will remain in a JSON or CSV Format

2 There will be an outside program to trigger this pipeline and call this function

3 Profiling for Budget and Box Office amounts remain valid.  The criteria for matching forms will remain unchanged

4 The approach to calculate release dates will remain the same

5 For fields such as running time, budget, and box office, the Kaggle Data Is more accurate than the Wiki Data.
