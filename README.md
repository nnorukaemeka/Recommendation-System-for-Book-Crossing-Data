# Recommendation-System-for-Book-Crossing-Data
Recommendation System for Book-Crossing happens to be the challenge problem I chose to solve for 2019 Machine Learning Fellow in Cape Town position. 

The Book-Crossing data comes from Cai-Nicolas Ziegler of IIF and can be found at http://www2.informatik.uni-freiburg.de/~cziegler/BX/.  More information about the data is available in Ziegler et al.:  Improving Recommendation Lists Through Topic Diversification. Cai-Nicolas Ziegler, Sean M. McNee, Joseph A. Konstan, Georg Lausen; Proceedings of the 14th International World Wide Web Conference (WWW '05), May 10-14, 2005, Chiba, Japan.

This repository contains two notebooks. In the first notebook, "Data cleansing", I will perform Data Cleansing and some Exploratory Analysis on the Book-Crossing Dataset using some techniques. The reason is to gain some intuition about the data. This also aims to prepare the data in a usable formate for the recommender system to provide book recommendations. 

The second notebook "BookCrossing_Recommender" uses the BookCrossing_Recommender.py to create a command-line user interface. The user is able to rate Books and gets recommendations based on the ratings. Since the dataset is sparse it works best if the user rates a lot of items. To provide the predictions we use surprise library (http://surpriselib.com/).
