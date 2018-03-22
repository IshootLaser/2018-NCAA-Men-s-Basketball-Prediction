# 2018-NCAA-Men-s-Basketball-Prediction
My first competition on Kaggle, predicting the outcomes of 2018 NCAA Men's basketball March Madness games.<br>
I tried to use a simple logistic regression model as baseline estimator. Then I tried to push the limit with a simple 3 layers fully connected neural network.The train and validation results seemed good but the model failed to generalize well on unseen data.<br>
I have tested various network architecture (3 ~ 4 layers, 10 ~ 60 hidden units per layer) but lands with this one, which I think generalizes the best on unseen data.<br>
Logistic regression produces extreme end results (either very close to 0 or very close to 1). Its prediction is bad on the leaderboard.<br>
The features that I used are: tourney seed, WOL rating and advanced stats (thanks to [Laksan Nathan's kernel](https://www.kaggle.com/lnatml/feature-engineering-with-advanced-stats).)
