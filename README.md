- The project's main aim was to create a model that could predict the chances of survival for passengers on the Titanic. This model was based on their personal and financial information.The goal was to find out which types of people were most likely to survive the sinking of the famous Titanic ship.

- To do this, we used two sets of data from Kaggle. The first set, called `train.csv`, had information about the survival status of 891 passengers. The second set, called `test.csv`, had information about an additional 418 passengers, but did not include information about survival. The aim was to train a model using the first set of data (`train.csv`), and then use this model to predict the survival of passengers in the second set (`test.csv`).How good the model was was evaluated using the Kaggle leaderboard.

- During the modelling phase, a range of algorithms were investigated to find the most accurate ones. The models used were Logistic Regression, Random Forest, Boosting Forest Model and Support Vector Machines (SVM).Logistic Regression was chosen because it can handle categories and its coefficients are easy to understand.Ensemble models, like Random Forest and Boosting, were better at predicting outcomes because they used lots of decision trees to spot complex patterns in the data.

- The final model was made better by cross-validation and changes to the settings, which stopped the model from overfitting and made sure it worked well with new data.To see how well the model could predict survival in the test set, the results were compared to the true results, which were not known during the training process.


