# OneLastCoffee

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

This is my last project of my Udacity's DataScience Nanodegree program. For this project, I was interestested in simulated data that mimics customer behavior on the Starbucks rewards mobile app to resolve the next question: 
Which are the main characteristics to predict if an user will take an offer in the App?

## File Descriptions <a name="files"></a>

The Data folder contains the data to work through the notebook. This is the data schema

**portfolio.json**
* id (string) - offer id
* offer_type (string) - type of offer ie BOGO, discount, informational
* difficulty (int) - minimum required spend to complete an offer
* reward (int) - reward given for completing an offer
* duration (int) - time for offer to be open, in days
* channels (list of strings)

**profile.json**
* age (int) - age of the customer 
* became_member_on (int) - date when customer created an app account
* gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
* id (str) - customer id
* income (float) - customer's income

**transcript.json**
* event (str) - record description (ie transaction, offer received, offer viewed, etc.)
* person (str) - customer id
* time (int) - time in hours since start of test. The data begins at time t=0
* value - (dict of strings) - either an offer id or transaction amount depending on the record


There is 1 Jupyter notebook available here to showcase work related to the above questions. The notebooks is exploratory in searching through the data pertaining to the questions showcased by the motivation project.  Markdown cells were used to assist in walking through the thought process for individual steps.  

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://medium.com/@juandiegocuellar02/starbucks-app-you-are-one-of-those-people-who-buys-only-when-they-recieve-offers-6a609d7df1f9).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to Udacity who gave it to me the data to work with.  Otherwise, feel free to use the code here as you would like! 

