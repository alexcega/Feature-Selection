# Feature-Selection

## Introduction
Reduce the columns used in a dataframe to work on a precise classification model.
In this project we make use of the Decision Tree Classifier.


## Used Dataframes

During the investigation 3 diferent datasets were used using different data science techniques and analizys, this being:

- Palmer Penguins
- Mushrooms
- Internet Advertisements

Each one of this were used for a classification model, using a genetic algorithm optains from an open source

### Palmer Penguins
In here the we get diferent informetion such as the island the penguin is from, the year, lenght of flippers, etc. The classification variable for this dataset is the species, having 3 different options:
- Adelie
- Chinstrap
- Gento

Using the 1+1 algorithm for the generetion of the vector representing the attributes to be used.

### Mushrooms 
The information represent 23 species of mushrooms and its characteristies. The data inside this dataset was completly cualitative so the columns needed to be encoded, remembering that the information was optain from [UC Irvine Machine Learning Repository](https://archive-beta.ics.uci.edu/dataset/73/mushroom)

The classification variable for this was to determin if a mushroom was edible or poisonus. The algorithm chose to work with was an genetic algorithm using a tournament selection for the next generations.

## Internet advertisment

Finally the ads dataset was optain thanks again to [UC Irvine Machine Learning Repository](https://archive-beta.ics.uci.edu/dataset/51/internet+advertisements )
In here we get 1558 columns and 3279 rows representing information from diferent internet websites.

For this task the model has to decide if the image is an advertisment or not, working with diferent attributes such as 

this instances were not equaly distributed, having more than 3 time "no ad" than "ad", so we use the Under-Sampling technique.