# Assignment04

This assignment trains a Decision Tree Model for estimating if a Titanic Passenger would survive or not, based on the data given in the linked csv.
Not all features are used in this model. The important features used are ['Pclass', 'Sex', 'Age', 'SibSp', 'Parch', 'Fare', 'Embarked']

The details about which features were chosen, and how missing values were handled, is included in the PDF. For optimal performance, run the Colab Notebook from scratch. 

The following evluation metrics were given based on the model:

Accuracy: 0.782

Precision: 0.727

Recall: 0.757 

The model is accurate in classification 78.2% of the time. The precision of 72.7% tells that the positive predictions are correct, or that 27% of positive indications will be false. Lastly, the recall of 75.7% says that 24% of unflagged data was missed by the model.

The confusion matrix from the model that was used to find these metrics is also included in the pdf.

