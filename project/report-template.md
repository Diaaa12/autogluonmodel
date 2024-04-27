# Report: Predict Bike Sharing Demand with AutoGluon Solution
#### Dia Ahuja

## Initial Training
### What did you realize when you tried to submit your predictions? What changes were needed to the output of the predictor to submit your results?
TODO: The score for my first model was 1.84007. It did not give any errors. potential errors could be due to having negative values in the predictions. I removed the negatives and it was successful. However the score was low.

### What was the top ranked model that performed?
TODO: The model WeightedEnsemble_L3 perfomed the best ranked with a score of 2.257957.

## Exploratory data analysis and feature creation
### What did the exploratory analysis find and how did you add additional features?
TODO:  I changed the datetime column with object dtype into datetime dtype.
I divided the datetime in month, day, year and hour.
I also converted informative season and weather data into categorical type.

### How much better did your model preform after adding additional features and why do you think that is?
TODO: by adding the additional features, the training of model became more efficient and the score improved from 1.84007 to 1.68645

## Hyper parameter tuning
### How much better did your model preform after trying different hyper parameters?
TODO: I tried tuning the hyperparameters - num_trials, scheduler and searcher. However the score didnt change by much.

### If you were given more time with this dataset, where do you think you would spend more time?
TODO: I will spend more time to hyperparameter tuning as there are many more ways in which I can improve my model and would like to explore those.

### Create a table with the models you ran, the hyperparameters modified, and the kaggle score.

I have provided the table as an image(as suggested in the project review) in a seperate file named "report-table"

**###Create a line plot showing the top model score for the three (or more) training runs during the project.**

The image is in a seperate file named "report-image2"

### Create a line plot showing the top model score for the three (or more) training runs during the project.

TODO: The image is in a seperate file named "report-image"

## Summary
TODO: Through this, I applied the concepts that were covered in the unit and improved the scores for the model one by one. Overall,this was a fun project and learned a lot by it.
