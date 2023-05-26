# sql-movies-project

The task of this project was to generate datasets to be used in MySQL with specific limitations.

Surnames of actors and directors were to be unique, thus the filtering of IMDBs datasets.
This was done in python.

Any choices were based on the assignment task.
Although some values could be randomised it uses IMDBs data.

A simple way of labelling nationality is first performed.
It uses predictive data based on US census data and randomly refines the information with deductions.

A NLP ML model is used on a name and nationality dataset from wikipedia to predict the nationality instead.
Some famous actors that survived the unique surname purge are tested using the IMDB library.
