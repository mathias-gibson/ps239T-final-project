# ps239T-final-project

#Short Description

Give a short, 1-2 paragraph description of your project. Focus on the code, not the theoretical / substantive / academic side of things.

Dependencies

List what software your code depends on, as well as version numbers, like so:.

R, version 3.1
Python, version 2.7, Anaconda distribution.
(In your scripts, includes commands that install required packages.)

Files

List all other files contained in the repo, along with a brief description of each one, like so:

Data

Code
01_collect-nyt.py: Collects data from New York Times API and exports data to the file nyt.csv
02_merge-data.R: Loads, cleans, and merges the raw Polity and NYT datasets into the Analysis Dataset.
03_analysis.R: Conducts descriptive analysis of the data, producing the tables and visualizations found in the Results directory.
Results

coverage-over-time.jpeg: Graphs the number of articles about each region over time.
regression-table.txt: Summarizes the results of OLS regression, modelling nyt on a number of covariates.
More Information

Include any other details you think your user might need to reproduce your results. You may also include other information such as your contact information, credits, etc.
