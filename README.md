# theBostonLagers
University of Kansas Bootcamp Project 1: Analysis of Ride-Sharing Data in Boston, MA
## Contents:
    
    Data Cleaning.ipynb
    Data Analysis.ipynb
    Project Proposal.docx
    Project Conclusions.docx
    Project Presentation.pptx
    Figures
    Resources

## Tools Used

    Jupyter Notebook
    Pandas
    Matplotlib
    SciPy Linear Regression
    DatetimePy Library

## Description
A. Data Cleaning.ipynb
    
1. Importation of a ride-sharing data set published by Kaggle user RaviMunde.
2. Use of the DatetimePy library to convert the 13-digit UNIX timestamp in order to determine the day of the week on which each data point was recovered.
3. Removal of extraneous columns not significant to the analysis.
4. Use of the DropNa function to remove about 60,000 columns missing essential data values.
5. Exportation of the cleaned data file for use in the analysis portion.

B. Data Analysis.ipynb

1. Importation of cleaned data file created in the Data Cleaning.ipynb procedure.
2. Use of Pandas GroupBy, Matplotlib, and SciPy Linear Regression functionality to determine how ride distance and ride price compare accross the various ride sources and destinations.
3. Use of Pandas and Matplotlib to create figures comparing the operations of Uber and Lyft in Boston, MA.
4. Incoportation of DatetimePy functionality to determine how Uber and Lyft demand is affected by the day of the week.
5. All resulting figures were saved to the Figures folder.