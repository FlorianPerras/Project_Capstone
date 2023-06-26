# Data Science Capstone Project - Starbucks challenge

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond common Python libaries.  The code should run with no issues using Python version 3.*.
The code can be found on Github: https://github.com/FlorianPerras/Project_Capstone

## Project Motivation<a name="motivation"></a>

This project uses a dataset from Starbucks containing user offer interactions, user data (anonymized) as well as different offers from Starbucks sent to customers. These datasets are used for creating a recommendation engine in order to create recommendations for Starbucks which shall lead to higher revenue by creating a positive user reaction on certain offers.
The project structure is like this:
- Data cleaning
- Data evaluation
- Set up FunkSVD algorithm (train and validate)
- Create recommendation engine for Starbucks

## File Descriptions <a name="files"></a>

- data/*: the three datasets provided by Starbucks
- Starbucks_Capstone_notebook.ipynb: The jupiter notebook containing the actual python code of the project
- userItemMatrix.p: The calculated userItemMatrix. This one can be loaded instead of recalculate it since the calculation time is quite high.
- test_df.p: The test dataset split out of the userItemMatrix. Also saved for time reasons.
- train_df.p: The train dataset split out of the userItemMatrix. Also saved for time reasons.
- pic1.png & pic2.png: Two png files used within the jupiter notebook

## Execution <a name="execution"></a>

To run the code simply open the jupiter notebook and make sure any version of Python 3.* is installed on your machine

## Acknowledgements<a name="acknowledgment"></a>

Must give credit to Starbucks for the data. 
I also want to thank Udacity for the great introduction and the great data science course. I learned a lot and it was really a challenge!

