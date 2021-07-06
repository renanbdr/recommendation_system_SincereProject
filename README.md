![alt text](https://github.com/renanbdr/recommendation_system_SincereProject/blob/main/cover.png?raw=true)

# Sincere recommender
## A Movie recommender system using hybrid clustering (k-means and fuzzy c-means) and SVD based on ratings

Final assignment of Infnet's Data Science Bootcamp (MIT - Data Science, Data Analytics & Machine Learning).

An experimental collaborative movie recommendation system developed on python using Kmeans, Fuzzy C-Means and SVD. The recommendation system was named Sincere and outlined promising results in **attacking data sparsity by focusing on suggesting interesting movies that may or may not be on that user's radar**.  

The files of this repository are divided in the following folders:

## Docs 
* Links to the bibliographic references 
* Final presentation (available in English and Portuguese)

## Data
Due to data size, links to google drive with said database were provided.

* Inputs - primary and secondary databases used as input for the analysis.
* Outputs - intermediate and final results of each stage of the process. Considering the large size of the databases, intermediate files were generated so that whoever wants to reproduce the analysis will be lesser affected by computational challenges issues.

## Code
### ETL
--> [sincere_etl_data_wrangling.ipynb](https://github.com/renanbdr/recommendation_system_SincereProject/blob/main/Code/sincere_etl_data_wrangling.ipynb)

### Clustering
--> [sincere_clustering.ipynb](https://github.com/renanbdr/recommendation_system_SincereProject/blob/main/Code/sincere_clustering.ipynb)

### Predicting
--> [sincereSVD.ipynb](https://github.com/renanbdr/recommendation_system_SincereProject/blob/main/Code/sincereSVD.ipynb)

### Results
--> [sincere_comparison.ipynb](https://github.com/renanbdr/recommendation_system_SincereProject/blob/main/Code/sincere_comparison.ipynb)

This is a bootcamp project, implemented in pairs. Thiago([@ThiagoCarvalho-81](https://github.com/ThiagoCarvalho-81)) and I worked together. 
The scope of the work was, in a 2-week period, use a different approach on a experimental recommender system using a public dataset and at least 3 algorithms.
