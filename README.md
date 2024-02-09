# Unsup_learning

BBC News Classification
Purpose: To classify news articles based using vectorization

excerpt:
Now for the actual project, I split my data using the traditional train, test, split.I do not include text from the test set unless I am predicting on them. But the model does not actually see them at all until that time.

Then performed matrix vectorization and NMF (Negative matrix vectorization) to transform and model the data. To begin I actually ran a whole bunch of these but they wont fit, well anywhere so I tried to keep the stuff that I thought made a bigger difference in the model error and accuracy scores. The reconstruction error is the difference between the training data and the reconstructed data. And the accuracy was.. well the accuracy score.

For the initial model the Frobenius parameter seemed to do okay, the kullback made the error astronomical and the itakura-saito is not there because it broke everything.
