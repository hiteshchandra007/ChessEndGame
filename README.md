# Chess End Game

* Rook endgames are the most common type of endgames there is in the
game of chess. These endgames take place in about in 50% of all the games.
The main idea is checkmate of black king with white king and white rook. This
should be done in less than 16 steps.

* The main aim of my project is to predict the outcome of the king-rook vs. king
endgame. For this I selected the dataset from UCI
(https://archive.ics.uci.edu/ml/datasets/Chess+%28King-Rook+vs.+King%29)
So my goal is to predict the outcome of the game whether the white king will
win the game in less than 16 moves or not. Here I am using classification
models to find the f score of each model and select the model which will
have high f score. Here the input parameter is given in the form of training
data.
The tasks involved in it are:
1. Download the data
2. Cleaning the data and removing the null data points, duplicated data rows.
3. Visualizing the data.
4. Split the data and train and test which classifier performs good on the
dataset based on the evaluation metric we have chosen.
5. Choose the best classifier that gives the best accuracy scores.

* Here mainly we will use three algorithms.
1. Decision Tree.(Benchmark Model)
2. Random Forest.
3. Support Vector Machine.
