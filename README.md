# SC1015 Miniproject - Video Game Sales
# Group Members
| Names         | Matric Number | Email                    |
| ------------- |:-------------:| ------------------------:|
| Darrus        | U2223371E     | DMOK006@e.ntu.edu.sg     |
| Charmain      | U2223590D     | C220186@e.ntu.edu.sg     |
| Shivani       | U2222698C     | RAJUSHIV001@e.ntu.edu.sg |


# About
This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on Video Games Sales. For detailed walkthrough and our group's findings, please view the [source code](/Code/VideoGamesProj.ipynb).
![SC1015_PPT](https://user-images.githubusercontent.com/34603548/231744531-90232357-a063-4050-8e23-7d1937ef4744.jpg)


# Objective
+ The objective of this project is to analyse the dataset of video game sales and gain insights into the factors that determine the success of video games.
+ The best machine learning model to predict the success of video games

# Models Used
+ Linear Regression (Baseline model)
+ Gradient Boosting Regression (Our Main Model)
+ K-Nearest Neighbors Regression
+ Random Forest Regression
+ Ridge Linear Regression


# Conclusions
+ Critic_Score have high correlation with the sales of a video game
+ Although Revenue, Earnings have high correlation they are not used for predicting as it is understood that higher revenue equates to higher sales
+ User Score and Year of Release of a video game are one of the lowest correlation with the sale of a video game
+ Hyperparameter tuning of Gradient Boosting took a very long time as it has many hyperparameters.
+ Hyperparameter tuning of Gradient Boosting did not improved the model's result significantly at all.

# What did we learn from this project?
+ Using of colab to collaborate
+ Gradient Boosting
+ Merging of datasets and how to handle null values
+ Which performance metric to use (Mean Absolute Error vs Mean Squared Error)

# Folder/Files Descriptions
+ Code
	+ [VideoGamesProj.ipynb](/Code/VideoGamesProj.ipynb)
		+ A Jupyter Notebook containing the main source code for the project.
+ Datasets
	+ [Video_Games_Sales.csv](/Datasets/Video_Games_Sales.csv)
		+ The Video Games Sales dataset that was used in the project. The dataset can be found [here](https://www.kaggle.com/datasets/rush4ratio/video-game-sales-with-ratings)
	+ [GamingCompanies.csv](/Datasets/GamingCompanies.csv.csv)
		+ The Large Video Game Companies dataset that was used in the project. The dataset can be found [here](https://www.kaggle.com/datasets/kkhandekar/large-video-game-companies)
+ Presentation Slides
	+ [SC1015_Miniproject_Slides.pptx](/Presentation%20Slides/SC1015_Miniproject_Slides.pptx)
		+ Our group's powerpoint slides for the project.

# Contributions
+ Darrus
	+ Mainly Machine Learning (Checkpoint 3 & 4)
	+ Merging of Datasets
	+ Some parts of Data Visualisation
+ Charmain
	+ Data Preprocessing (Checkpoint 2)
	+ Data Visualisation (Checkpoint 2)
+ Shivani
	+ Detailed Introduction of Project (Checkpoint 1)
	+ Data Visualisation (Checkpoint 2)
# Reference

+ Santos, G. (2022, October 24). How to choose the number of estimators for gradient boosting. Medium. Retrieved April 13, 2023, from https://towardsdatascience.com/how-to-choose-the-number-of-estimators-for-gradient-boosting-8d06920ab891 
+ Brownlee, J. (2020, August 14). A gentle introduction to the gradient boosting algorithm for machine learning. MachineLearningMastery.com. Retrieved April 13, 2023, from https://machinelearningmastery.com/gentle-introduction-gradient-boosting-algorithm-machine-learning/ 
+ Kirubi, R. (2016, December 30). Video game sales with ratings. Kaggle. Retrieved April 13, 2023, from https://www.kaggle.com/datasets/rush4ratio/video-game-sales-with-ratings 
+ Koustubhk. (2022, June 15). Large video game companies. Kaggle. Retrieved April 13, 2023, from https://www.kaggle.com/datasets/kkhandekar/large-video-game-companies 

