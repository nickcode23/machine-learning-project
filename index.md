# Pokémon Combat Results Machine Learning Project   
## [**Project Link**](https://github.com/nickcode23/machine-learning-project.git)











## Why we do this
Pokémon was a game series developed by Nintendo and was later adapted into animations and movies. Pokémons are creatures of all shapes and sizes in the wild or raised by trainers. In many Pokémon games, the player is a trainer who catches Pokémons, trains them, and battles against other trainers' Pokémons. Pokémon battles are turn-based. Each battle consists of repeated turns, and each turn requires all participants to choose an action to take. The outcomes of those actions are revealed immediately through changes in Pokémon status, such as a decrease in hitpoint, which directly influence the rest of the combat. Eventually, the Pokémon reaches zero hit points first loss, and the one that lasts longer wins (The Cave of Dragonflies, 2019). Inspired by the game process, we were curious about how well the combat results can be predicted given the characteristics of two Pokémons. 


## How we do this
We obtained Pokémon datasets from Kaggle (Pokémon- Weedle's Cave | Kaggle), the datasets contained descriptive data of 800 Pokémons and 50,000 combat results. Classification methods including **logistic regression**, **Linear Discriminant Analysis (LDA)**, **Quadratic Discriminant Analysis(QDA)**, **K-Nearest Neighbors(KNN)**, **Support Vector Machines(SVM)**, and **tree models** are used to predict the combat results.


## Final Result
We observed that **Random Forest** was the most effective model in predicting winners of Pokémon combats which achieved 96.68% accuracy, with speed difference between Pokémons as the most important predictor.





