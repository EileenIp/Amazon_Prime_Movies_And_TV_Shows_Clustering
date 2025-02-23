# Amazon Prime Movies And TV Shows Clustering - Unsupervised ML
---

![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)
![Microsoft Office](https://img.shields.io/badge/Microsoft_Office-D83B01?style=for-the-badge&logo=microsoft-office&logoColor=white)
![Microsoft Word](https://img.shields.io/badge/Microsoft_Word-2B579A?style=for-the-badge&logo=microsoft-word&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white)
![Numpy](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit_Learn](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Scipy](https://img.shields.io/badge/SciPy-654FF0?style=for-the-badge&logo=SciPy&logoColor=white)
![Matplotlib](https://custom-icon-badges.demolab.com/badge/Matplotlib-71D291?logo=matplotlib&logoColor=fff&style=for-the-badge)

---

## Problem Overview

This dataset consists of tv shows and movies available on Amazon Prime as of 2019. The dataset is collected from Flixable which is a third-party Amazon Prime search engine.

In 2018, they released an interesting report which shows that the number of TV shows on Amazon Prime has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.

Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.

In this project, required to do:

- Exploratory Data Analysis.

- Understanding what type content is available in different countries.

- Is Amazon Prime has increasingly focusing on TV rather than movies in recent years.

- Clustering similar content by matching text-based features.

---

## Project Summary

This dataset consists of tv shows and movies available on Amazon Prime as of 2021. The dataset is collected from Flixable which is a third-party Amazon Prime search engine.

In 2021, they released an interesting report which shows that the number of TV shows on Amazon Prime has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.

Initially I have start with understanding the dataset, then I clean the data to make analysis ready.

Explore the data and understand the behaviour of the same.

Then I have prepare the dataset for creating clusters by various parameters wherein I can remove stop words, white spaces, numbers etc. so that I can get important words and based on that i shall form clusters.

Later I have used the silhouette method and k-means elbow method to find optimal number of clusters and built recommender system by cosine similarity and recommended top ten movies.

---

## Conclusion

The objective of the project was to cluster TV shows and movies based on their similarities and differences, with the ultimate goal of creating a content-based recommender system that recommends 10 shows to users based on their viewing history. Some key points from the project include:

- Exploring the dataset consist of 9968 records and 12 attributes, with a focus on missing value imputation and exploratory data analysis (EDA).

- The analysis revealed that Amazon Prime has a greater number of movies than TV shows, with a rapidly growing collection of shows from the United States.

- To cluster the shows, I have selected six key attributes: director, cast, country, genre, rating, and description (all are categorical variables). These attributes were transformed into a 9000-feature TF-IDF vectorization, and Principal Component Analysis (PCA) was used to address the curse of dimensionality. Captured more than 80% of the variance by reducing the components to 2500.

- Next, I used K-Means and Agglomerative clustering algorithms to group the shows. The elbow method confirmed that the optimal number of clusters was 6 for K-Means, however for Silhouette score analysis it was 5.

- In Agglomerative clustering the optimal number of clusters was also 6, which I visualized with a dendrogram.

- Continued all the efforts by creating a content-based recommender system using the similarity matrix obtained through cosine similarity.

The recommender system offers personalized recommendations based on the type of shows the user has watched and provides the user with ten top-notch suggestions to explore.

---

## Author

- [Eileen Ip](https://www.linkedin.com/in/eileen-ip/)
