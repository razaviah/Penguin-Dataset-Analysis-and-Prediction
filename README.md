# Penguin-Dataset-Analysis-and-Prediction


Please refer to the official [Github page](https://github.com/allisonhorst/palmerpenguins/blob/master/README.md) for details and license information. The details below have also been taken from there.

## Summary of Data:

The data folder contains a csv file: penguins_size.csv
- penguins_size.csv: Simplified data from original penguin data sets. Contains variables:
- species: penguin species (Chinstrap, Adélie, or Gentoo)
    - culmen_length_mm: culmen length (mm)
    - culmen_depth_mm: culmen depth (mm)
    - flipper_length_mm: flipper length (mm)
    - body_mass_g: body mass (g)
    - island: island name (Dream, Torgersen, or Biscoe) in the Palmer Archipelago (Antarctica)
    - sex: penguin sex
            
What are culmen length & depth?
    The culmen is "the upper ridge of a bird's beak" (definition from Oxford Languages).

## Task:
Predict the class of penguin species

## Questions that have been answered by this project:

- Perform a detailed exploratory data analysis on the dataset
- Experiment using two different ratios of training, validation and test data ie 60-20-20 & 80-10-10. On the two different split ratios do the following
    - Implement Grid Search CV to find optimal hyperparameters for any 3 algorithms (out of LR, SVM, MLP, RF, Boosting)
    - Plot the learning curve using the learning curve function from scikit-learn to analyze the model performance. The plot should show the training score           and cross validation score against the number of training examples.
    - Analyze the results on Validation set and Test set and mention which model performed the best and why?
    - Compare the performance of models(using precision, recall, accuracy, latency).
- What was the best proportion or split ratio of data from the set of experiments you conducted and why?


## Citation:
Gorman KB, Williams TD, Fraser WR (2014) Ecological Sexual Dimorphismand Environmental Variability within a Community of Antarctic Penguins (Genus Pygoscelis). PLoSONE 9(3): e90081. doi:10.1371/journal.pone.0090081


