# Enhanced Alpha Development
 Feature engineer a multitude of different features using Sci-Kit Learn.
* Create alpha factors using zipline, create target (labels) for model (5 day shifted returns).
* Fit tree based models and look for potential rooms for improvement. 
*  Build a custom sci-kit learn class which inherits from VotingClassifier to fit on non-overlapping data.
* Instantiate custom class with random forest. Fit model using the ensemble of non-overlapping trees. 
* The model can now accurately predict if a stocks future (5 day) returns, will be in the top quantiles. 
* This factor is called 'AI Alpha', and has a sharpe >2 on test data.
