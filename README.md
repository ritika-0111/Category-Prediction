# Category-Prediction  

## Aim:  
Predict the product category.  
  
## Dataset:  
Dataset used in this repo can be downloaded from the given link : https://docs.google.com/spreadsheets/d/1pLv0fNE4WHokpJHUIs-FTVnmI9STgog05e658qEON0I/edit?usp=sharing  
This dataset consists of 15 features that are:
 1) uniq_id  
 2) crawl_timestamp  
 3) product_url  
 4) product_name  
 5) product_category_tree  
 6) pid  
 7) retail_price  
 8) discounted_price  
 9) image  
 10) is_FK_Advantage_product  
 11) description  
 12) product_rating  
 13) overall_rating  
 14) brand  
 15) product_specifications  
  
## About this Repository:  
Task 3: NLP
Assignment Details-
Use a given dataset to build a model to predict the category using description. Write code in python. Using Jupyter notebook is encouraged.  
  
About Data : You have to clean this data, In the product category tree separate all the categories, figure out the primary category, and then use the model to predict this.  

## Strategy:  
1) Read the data through the given csv file.  
2) Data Cleaning. [Remove duplicates items, Drop rows with null values]  
3) Save the obtained data to pickle file.  
4) Separate the primary category from the product category tree.  
5) Text pre-processing.  
6) Splitting data into train and test data.  
7) Featurization. [BAG OF WORDS, TF-IDF]  
8) Apply NaiveBayes classifiers.  
9) Compare model score of BOW and TF_IDF vectorizer.  
10) Predict product category.  
  
