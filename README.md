# Louisville Free Public Library

## Example Project - Cleaning Data

This is an example project for Code Louisville Data Analysis 1.

##  Requirements

- Python 3.9 or higher
- Jupyter and Pandas

## Instructions

1. Fork the repo to your GitHub account
1. Clone your fork of the repo to your computer
1. Change into the project directory `$ cd lfpl-clean`
1. Create a virtual environment, activate it, and install the `requirements.txt`
1. View the `explore.ipynb` notebook
1. Run the clean.py script: `$ python3 clean.py data/test.csv results/test_clean.csv`

NB: All commands are linux-specific and may need to be altered for your OS.

## Challenges

Review the details captured in the `explore.ipynb` notebook and add code to the `clean.py` file to:
1. Remove unneeded columns (ISBN, ReportDate)
1. Remove records with empty and invalid PuublicationYear or ItemCollection.
1. Update incorrect values (PublicationYear 2109 -> 2019)
1. Add genre and audience columns
