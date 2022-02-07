# Udacity Data Scientist Capstone

The EU aims to be climate-neutral by 2050.

I found a dataset with energy source balance on Kaggle (data ranging from 1990 to 2019): https://www.kaggle.com/gpreda/energy-balance-in-europe

# Content:

## data.zip 

- Energy consumption and production balance in Europe between 1991 and 2019, per country, energy balance code, energy production source, unit, and geography: energy_balance_eu.csv;
- Energy balance dictionary of terms - nrg_bal_dict.csv;
- Energy production sources dictionary of terms - siec_dict.csv; (not required for the purposes of this exercise)

>> code.ipynb
Jupyter notebook with code and comments

>> rf_drafts.pdf
Export from Jupyter notebook with code and comments. Illustrates the attempts (and failure) to model with Random Forest. Not required 


## These are the questions that's I'd like to answer:

1. Can we group the energy sources by their climate impact?
2. Can we observe a trend on the historic data in each of the identified groups?
3. Can we predict trend of energy consumption in each of the groups until 2050?
4. How does the prediction correspond to the goal of climate neutrality in 2050?


# Instructions:

Unpack data.zip archive into corresponding folders.

Use code.ipynb to run and read cells.

Read my blog on Medium: 

# Limitations:

Many countries seem to be able to achieve the set goal. There are countries like Albania though, for example, which have a comparatively low consumption currently and an upward trend on all groups of sources (climate-damaging being most prominent). Others, like Finland, evidently invest into green energy and are closer to the goal than many others. Obviously, our study has a lot of limitations and assumptions: for example, we do not have access to the variables that determine the production of energy in various sources, e.g. a colder winter can have a significant upward impact, however, we will not be able to identify the reason. Also, the population grows, the consumption overall changes, so the observed trend in the overall energy source usage does not tell us anything about consumption per household, it may go up or down. Finally, we do not know what may or may not impact the trend in the future. Assuming everything stays in the same range, the forecast is quite optimistic. 

# Contributing:

Changes and suggestions for a better model are welcome. For major changes, please open an issue first to discuss what you would like to change.
