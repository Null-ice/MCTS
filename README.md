# MCTS

Link to Kaggle competition here: https://www.kaggle.com/competitions/um-game-playing-strength-of-mcts-variants/leaderboard

Brief writeup here: https://www.kaggle.com/competitions/um-game-playing-strength-of-mcts-variants/discussion/549624

Link to the Kaggle notebook here: https://www.kaggle.com/code/mohammad2012191/um-inference-nb-9th-place-solution

We placed 9th place of 1610 teams with our Light Gradient Boosted Dart model and Catboost model enemble - Both models were hand tuned from default and did not use early stopping. Changes were made in small increments to avoid overfitting the training dataset. Advancements were attempted with Optuna but cv did not change by much so we committed to the hand tuning results.
