# Input-selection-methods

In this repository, the implementation of each input selection method is provided. Each method assigns an importance metric to each input, then, they are aranged in decreasing order, allowing to select the N most important inputs.
In addition, an optimization of the training hyperparameters is done, to ensure that the models are the best possible without incurring in overfitting.
To continue with, 5 models are trained with different random seeds for the training subset according to the refined hyperparameters.
Finally, the predictions for each model are evaluated and plotted.
For the top 4 selected methods, a study on the noise sensitivity is also conducted at the end.
