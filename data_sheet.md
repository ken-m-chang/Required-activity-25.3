# Datasheet Template

## Motivation

The dataset contains the monthly revenue numbers for a specific client in the company, the dataset is meant to serve as data for a neural network machine learning model to learn patterns and to predict future revenue for this client.

 
## Composition

The dataset represent revenue data from three different sources for each month, covering one year in total
- Marketing
- Non Marketing
- Training

There are a total of 12 instances for each of the source, corresponding to each month of the year.

The data for Training is found to be missing for the month of November and December, likely due to human error.

The data is not confidential.


## Collection process

The dataset was created by me through exporting the revenue history for this client from the company database.
The data consist of revenue data over the year 2022, I wanted to have a relatively small dataset to work with, so that I could focus more on hyperparameter tuning.


## Preprocessing/cleaning/labelling

The raw data consists of the revenue figures, time-frames, and some other project related details which are unnecessary, for example the client code, project manager username, currency, etc. Only the revenue figures and time-frames are necessary data to be kept.

Data went through some postprocessing steps:
- Cleaned by stripping the unnecessary columns
- Added new columns to represent a time-window
 
## Uses

This dataset is probably only useful for predicting the revenue for the specific client in our company.
This dataset doesn't contain any sensitive data that might lead to any specific groups or individuals being treated unfairly.


## Distribution

The dataset is not to be distributed, its sole purpose is to help create machine learning models to help the company make better decisions.


## Maintenance

The dataset is not maintained and will not be updated.

