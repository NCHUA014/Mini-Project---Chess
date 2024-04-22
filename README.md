Subject of project:
Using a dataset of 20000 records of online chess game

Things that were done in the project file:
- Cleaning of column titles
- Changing Increment code format to time control
- Exploratory analysis, dropping unnecessary columns
- Plotting graphs of 2 columns: turns/white rating

Machine learning:
- Selecting games where rating > 2000
- Removing Drawn games
- Creating new column: 'Is White Winner'
- Creating one-hot encoded columns for opening types
- Plotting a binary classification tree (Predictor: 222 one-hot encoded columns of openings, Response: Is White Winner)
- Plotting a confusion matrix
  
Outcome:
- Success in helping us understand which opening favours which side
- Confusion matrix's evaluation  
