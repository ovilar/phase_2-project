# My Phase 2 Project for Flatiron School
This is my Phase 2 Project for Flatiron School's Data Science Program

## OVERVIEW
I investigate a dataset of housing prices in King County - WA. Using a
regression framework, under two specific settings: causal and prediction I
delineate which factors are the most relevant to housing prices and how can
one accurately predict the price of a real state in King County.


## BUSINESS UNDERSTANDING
The purchase of a house is one of the biggest investments that one could make.
House as an asset is deeply ingrained in our culture. As such, the relevance of
point out which features are the most representative when assessing a property's
value are paramount.

I argue that the housing price analysis is relevant for a wide array of audiences, such as: realtors,
constructors, investment agents and the general public that have an interest
or live in the King County area. 

## DATA AND ANALYSIS
I use the 'kc_house_data.csv' provided from Flatiron School's repository:
<a href='https://github.com/ovilar/dsc-phase-2-project-v2-3'>original repo</a>.

Missing value, encoding and transformation is perfomed on this dataset. The
final dataset has more than 20,000 rows and 200 columns.

## REGRESSION FRAMEWORK
I perform two regression frameworks: a causal inference approach - where I
delineate which set of features best represent the price of a house in King County.
Precisely, the living size and lot area are the best numerical features to indicate
the price of real estate. In tandem, whether a house was renovated/or was
recently renovated, has an excellent view and it is in excelent condition,
is a mansion but with fewer bedrooms but has more than 3 bathrooms in Mercer
Island will explain around 82% of its price!

After our causal approach, a prediction framework is studied. For this purpose,
a new set of tests and procedures (train-test split, transformation, polynomial
features) are applied. I also investigate the ability of the prediction model
to provide a house price in King County based on its features.

## CONCLUSION

## INSTRUCTIONS
This repository provides basic guidelines on how to navigate through this notebook
and its material. For the sake of space, I do not make the dataset available.

You will find: presentation files, juyter notebook with all the code, this
readme file and images.
