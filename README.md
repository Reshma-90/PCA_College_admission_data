# PCA_College_admission_data
This repo explains step by step process of principal component analysis on a dataset that contains information of various colleges.

The head of the dataset looks like:
![image](https://user-images.githubusercontent.com/95558910/146539415-554cd1e2-f847-489b-ba1b-07c9bdf54644.png)
- There are total 777 rows and 18 columns in the dataset.
![image](https://user-images.githubusercontent.com/95558910/146541369-e0b5efaf-1831-4d30-ac68-da16e8caeb01.png)
- From the info it is inferred that there are no null values in the dataset and all the variables in the dataset are continuous except Names.
- Univariate analysis and Bivariate analysis has been performed on the dataset.
- As PCA is impacted by scaling, it is performed by using zscore.
- PCA has been performed using sklearn.decomposition to calculate eigenvectors and eigenvalues.
- Cumulative values of eigenvalues has been calculated to decide number of principal components.
![image](https://user-images.githubusercontent.com/95558910/146543106-786f025f-5f04-4770-a338-ee055c2d08a2.png)
![image](https://user-images.githubusercontent.com/95558910/146543393-5b24f760-f6b8-49c8-ad45-291ef11fc75b.png)
- It is observed from above output that only 7 PCs out of 17 contribute 85% of data. Hence 7 PCs has been selected.
