# Drug Decriminalization Project
Completed for DSCI 311 at the University of Oregon, Dec 2024.

## Project Overview

This project is an exploration of the relationship between narcotic crime rates and drug-related death counts both in Oregon and generally in the United States. The data used in
this project was provided by the FBI and CDC. In 2020, Oregon chose to decriminalize the posession of drugs when held in minimal quantity, which inspired me to look at the publicly
available data on the topic to understand any underlying trends which we might observe. Attending the University of Oregon and currently living in Eugene, OR, this project is something 
that I find very interesting and close to home.

## Sections

All work on this project was primarily completed within the JupyterNotebook file `Proj2.ipynb`. 

- **Exploration**  
  In this section, I primarily clean and view my datasets, examining various distributions and relationships at first glance. First I explore the FBI dataset on Narcotic Crime Rates,
  then the CDC data on drug-related death counts, and finally the relationship between these two datasets.

- **Inference**  
  In the above section, I noticed that the relationship between narcotic crime rate and drug-related death counts appears to differ drastically if the data provided was before or
  after the year 2020. I employ hypothesis testing to quantify/test the significance of this observed difference.

- **Prediction**  
  In the inference section above, I found a significant (yet weak) monotonic relationship between narcotic crime rate and drug-related death counts after the year 2020. Here, I attempt
  to predict drug-related death counts base on the narcotic crime rate. Although I was largely unable to create a successful and functional model, in this section (so far) I have
  attempted to train logistic, exponential, and power law models (separately) to my distribution of the relationship between narcotic crime rate and drug-related death counts. 

### Applications/Languages
- JupyterNotebooks
- Python

### Author
Myriah Hodgson <mhodgson@uoregon.edu>
