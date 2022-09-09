# Regressio Model - Housing Price Project

## OVERVIEW
I investigate a dataset of housing prices in King County - WA. Using a
regression framework, under two specific settings: causal and prediction. I
delineate which factors are the most relevant to housing prices and how can
one accurately predict the price of a real state in King County.

## BUSINESS UNDERSTANDING
The purchase of a house is one of the biggest investments that one could make.
House as an asset is deeply ingrained in our culture. As such, the relevance of
pointing out which features are the most representative when assessing a property's
value are paramount.

I argue that the housing price analysis is relevant for a wide array of audiences, such as: realtors,
constructors, investment agents and the general public that have an interest
or live in the King County area. 

## DATA AND ANALYSIS
I use the 'kc_house_data.csv' provided from Flatiron School's repository:
<a href='https://github.com/learn-co-curriculum/dsc-phase-2-project-v2-3'>original repo</a>.

Missing value, encoding and transformation is perfomed on this dataset. The
final dataset has more than 20,000 rows and 200 columns. The overall location distribution is highly concentrated around the Seattle area.
<img src = 'https://github.com/ovilar/phase_2-project/blob/main/img/figure00.jpg' alt = "City-Town concentration">

## REGRESSION FRAMEWORK
I perform two regression frameworks: a causal inference approach - where I
delineate which set of features best represent the price of a house in King County.
Precisely, the living size and lot area are the best numerical features to indicate
the price of real estate. In tandem, whether a house was renovated/or was
recently renovated, has an excellent view and it is in excelent condition,
is a mansion but with fewer bedrooms but has more than 3 bathrooms in Mercer
Island will explain around 82% of its price!

After our causal approach, a prediction framework is studied. For this purpose,
a new set of tests and procedures (train-test split, transformation, etc) are applied. I also investigate the ability of the prediction model
to provide a house price in King County based on its features.

From this exercise, it is clear that an oversaturated model can yield good explanatory power, at the expense of being able to predict the prices of out
of sample property. As such, I drop a few categorical variables then reaching a good balance between fit and prediction.

## CONCLUSION
For all stakeholders: the most valuable houses in King County share the features of being renovated, with excellent view
and quality, if it was a recently built, 2.5 floor Mansion in Mercer Island. Also, the property has fewer bedrooms and
3 bathrooms. With this information in mind, one could guide their investment decisions. Finally, this conclusion can be thought of in a reversed fashion. With that in mind, one can list the most undervalued house within King County - WA.

From the prediction standpoint, since our data is skewed towards properties from the Seattle area, it has better predictive
features within this area. In order to be generalized, some categorical features (such the year that it was built) had to
be sacrificed.

### Further Research
The use of polynomial features, aggregating demographic information and other.  

## INSTRUCTIONS
This repository provides basic guidelines on how to navigate through this notebook and its material. For the sake of space, I do not make the dataset available.

Here you will find:
<ul>
<li><a href= "https://github.com/ovilar/phase_2-project/blob/main/presentation.pdf">Presentation file</a>;</li>
<li>Jupyter Notebook;</li>
<li>README.md file;</li>
<li> A .gitignore - <a href = "https://gist.github.com/octocat/9257657">taken from here</a>;</li>
<li>Image Folder.</li>
</ul>

Feel free to reach out if you have any critique, suggestion or correction.
