# Netflix-TV_Show-Movies-Clustring.
**AlmaBetter Verfied Project**

![image](https://d1y8sb8igg2f8e.cloudfront.net/images/shutterstock_703724362.min-800x800.jpg)


# **Abstract**

Netflix is a company that manages a large collection of TV shows and movies, streaming it anytime via online.
This business is profitable because users make a monthly payment to access the platform. However, customers
can cancel their subscriptions at any time. Therefore, the company must keep the users hooked on the platform
and not lose their interest. This is where recommendation systems start to play an important role, providing
valuable suggestions to users is essential.

# **Introduction**

Netflix’s recommendation system helps them increase their popularity among service providers as they help
increase the number of items sold, offer a diverse selection of items, increase user satisfaction, as well as user
loyalty to the company, and they are very helpful in getting a better understanding of what the user wants.
Then it’s easier to get the user to make better decisions from a wide variety of movie products. With over 139
million paid subscribers (total viewer pool -300 million) across190 countries, 15,400 titles across its regional
libraries and 112 Emmy Award Nominations in 2018 — Netflix is the world’s leading Internet television
network and the most-valued largest streaming service in the world. 

# 📋 **Problem Statement**

This dataset consists of TV shows and movies available on Netflix as of 2019. The dataset is collected from
Flexible which is a third-party Netflix search engine.
In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly
tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since
2010, while its number of TV shows has nearly tripled.
Variables


# **Objective**

Netflix Recommender recommends Netflix movies and TV shows based on a user's favorite movie or TV
show. It uses a Natural Language Processing (NLP) model and a K-Means Clustering model to make these
recommendations. These models use information about movies and TV shows such as their plot descriptions
and genres to make suggestions. The motivation behind this project is to develop a deeper understanding of
recommender systems and create a model that can perform Clustering on comparable material by matching
text-based attributes. Specifically, thinking about how Netflix create algorithms to tailor content based on user
interests and behavior.

## **Appraoch Pipeline**

Exploratory Data Analysis (EDA): In this part we have done some EDA on the features to see the trend.

Data Processing: In this part we went through each attributes and encoded the categorical features.

Model Creation: Finally in this part we created the various models. These various models are being analysed and we tried to study various models so as to get the best performing model for our project.

## 💾 **Project Files Description**

This Project includes 1 colab notebook and 1 Pdf of presentation.

### **Executable Files:**
 - Includes Exploratory Data Analysis and all algorithms which are used in this project.
 - (https://github.com/Chetanrajput1331/Netflix-TV_Show-Movies-Clustering/blob/main/_Netflix%20Capstone%20projects.ipynb)

 - Includes pdf of the presentation of the project.
 - (https://github.com/Chetanrajput1331/Netflix-TV_Show-Movies-Clustering/blob/main/PRESENTATION%20NETFLIX.pptx)

### **Output:**
Google Colab -(https://github.com/Chetanrajput1331/Netflix-TV_Show-Movies-Clustering/blob/main/_Netflix%20Capstone%20projects.ipynb)- All the outputs are visible in the provided colab notebook.

## 📋 **Execution Instruction**

The order of execution of the colab notebook is as follows:

1).ipynb

First, click on the open in colab button present on the top center of the notebook.

In this .ipynb file, we have -

• EDA on Book Recommendation system.

• Applying different ML models

• Conclusion

**2) Kaggle Dataset**

Downlaod the dataset from kaggle through provided link.Then, connect to the runtime and execute the cell to mount the drive or upload the data file to the current runtime.

**3) Cell Path**

Finally, delete the path in the dataset loading cell and replace it with the path of your current data file. Run each cell to see the output below it.

## **Conclusions**

• There are about 70% movies and 30% TV shows on Netflix.

• The United States has the highest number of content on Netflix by a huge margin followed by India.

• Raul Campos and Jan Sulter collectively have directed the most content on Netflix.

• Anupam Kher has acted in the highest number of films on Netflix.

• Drama is the most popular genre followed by comedy.

• More of the content is released in holiday season - October, November, December  and January.

• The number of releases have significantly increased after 2015 and have dropped in 2021 because of Covid 19.

• NULL HYPOTHESIS -The number of TV shows on Netflix have tripled and number of movies have reduced by 2000 between 2010 and 2018. (REJECTED)

• By using Sillhouette's score and Elbow method , we generated optimal of 20 clusters
for K Means and from Dendogram , 6 clusters were generated.

• In both the cases, one cluster accounts more than 3000 points whereas in other
clusters the points were unevenly distributed. 3.For Tfidf K Means is best for
identification than Hierarchical as the evaluation metrics also indicates the same.

## 📜 **Credits**

Chetan Rajput|Anas| Sarthak Rastogi

## 📚  **References**

https://medium.com/analytics-vidhya/netflix-movies-and-tvshows-exploratory-data-analysis-eda-and-visualization-using-python-80753fcfcf7

https://www.analyticsvidhya.com/blog/2021/06/tv-shows-analysis-netflix-prime-video-hulu-and-disney/
