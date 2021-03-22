# Hepatit Patients or Blood Donors Data Set 

The data set contains laboratory values of blood donors and Hepatitis C patients and demographic values like age. I am trying to determine whether instance is Hepatitis C patient or blood donor with machine learning algorithms. First I will do data cleaning and preparation and after that EDA. Finally I will do implementation of machine learning algorithms.

Example from dataset:

<img width="685" alt="Ekran Resmi 2021-03-22 18 02 44" src="https://user-images.githubusercontent.com/79477750/112010931-d0a78100-8b38-11eb-82f4-261583bec1bc.png">

Heat map of missing values:

<img width="693" alt="Ekran Resmi 2021-03-22 18 06 38" src="https://user-images.githubusercontent.com/79477750/112011475-5aefe500-8b39-11eb-9ced-752c9dad66bb.png">

Data set example after changing missing values and making dummie variables for categories

<img width="590" alt="Ekran Resmi 2021-03-22 18 07 40" src="https://user-images.githubusercontent.com/79477750/112011634-7f4bc180-8b39-11eb-9c43-23988a0da612.png">

All categories we want to determine:

<img width="732" alt="Ekran Resmi 2021-03-22 18 09 55" src="https://user-images.githubusercontent.com/79477750/112011957-cfc31f00-8b39-11eb-8d11-37b598f1fe64.png">

After these resulst we understand that data set is not balanced. There are lots of blood donors but few patients.

Pearson's correlation heat map for all features with their correlation values:

<img width="732" alt="Ekran Resmi 2021-03-22 18 12 03" src="https://user-images.githubusercontent.com/79477750/112012272-1ca6f580-8b3a-11eb-92e6-64e3b66b95fc.png">

<img width="614" alt="Ekran Resmi 2021-03-22 18 13 54" src="https://user-images.githubusercontent.com/79477750/112012588-5ed03700-8b3a-11eb-9ef6-fd4ea47d6d1d.png">

<img width="614" alt="Ekran Resmi 2021-03-22 18 13 16" src="https://user-images.githubusercontent.com/79477750/112012480-495b0d00-8b3a-11eb-8a6b-3fd289a4e26e.png">

Confusion matrix and classification table with random forest before feature selection:

<img width="481" alt="Ekran Resmi 2021-03-22 18 14 28" src="https://user-images.githubusercontent.com/79477750/112012672-73143400-8b3a-11eb-8a44-c3412245474b.png">

Confusion matrix and classification table with random forest after feature selection:

<img width="481" alt="Ekran Resmi 2021-03-22 18 15 36" src="https://user-images.githubusercontent.com/79477750/112012873-9b039780-8b3a-11eb-8ac2-4e60b488898b.png">

Confusion matrix and classification table with SVM before feature selection

<img width="481" alt="Ekran Resmi 2021-03-22 18 20 34" src="https://user-images.githubusercontent.com/79477750/112013704-4d3b5f00-8b3b-11eb-9ea6-3cabf13369e9.png">


Confusion matrix and classification table with SVM after feature selection:

<img width="481" alt="Ekran Resmi 2021-03-22 18 19 34" src="https://user-images.githubusercontent.com/79477750/112013546-29781900-8b3b-11eb-95d3-75919e27c4e3.png">


