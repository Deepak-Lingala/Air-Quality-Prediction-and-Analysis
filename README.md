# Air-Quality-Prediction-and Analysis

Air Quality has been predicted over Ahmedabad, India using classical machine learning algorithms.

The dataset containing various meteorological and air quality parameters was compiled using the CAMS GLobal Reanalysis Data - EAC4 (https://ads.atmosphere.copernicus.eu/cdsapp#!/dataset/cams-global-reanalysis-eac4?tab=form). An Exploratory Data Analysis (EDA) was performed to visualize relationships between different features of the dataset. Correlation analysis & Principal Component Analysis (PCA) were applied on the dataset to select the most important features from the dataset. Various machine learning models such as linear models, kernel-based models, ensemble models were developed and evaluated via metrics such as r^2 score, mean absolute error, mean absolute percentage error, root mean square error using scikit-learn library of python. Gradient Boosting models were observed to perform best on the dataset.

References:

[1]	Kumar, K., Pande, B.P. Air pollution prediction with machine learning: a case study of Indian cities. Int. J. Environ. Sci. Technol. (2022). https://doi.org/10.1007/s13762-022-04241-5

[2] Saba Ameer1, Munam Ali Shah1 , Abid Khan1 ,Houbing Song 2, (Senior Member, IEEE), Carsten Maple 3,Saif Ul Islam 4, and Muhammad Nabeel Asghar5,“Comparative Analysis of Machine Learning Techniques for Predicting Air Quality in Smart Cities” ,June 26, 2019, Volume 7, 2019
