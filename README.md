# Model building for a oceanic data to predict the hieght of the wave 

1) we will dive into filling nan values for various type of data by analyzing the distribuion <br>
2) Then removing the outliers using iqr method, where the data which below the 25% and above the 75% of the data are removed using iqr method <br>
3) Attribute selection based on univariate selection. <br>
   ->we will aslo see which attribute selection method we need to use based on the structure of data we have <br>
4) Rescaling the data based on the skewness<br>
   ->both minmaxscaler and standard scaler is used<br>
5) Using kfoldcrossvalidation which is gold technique to evaluate the model <br>
6) I used to knn regressor as it finds a good prediction for non-linear data <br>

(Note* : You can also experiment with multiple techniques and methods to find out the best method for your data, no method is universal for any thing)
=> After going through this repo, you will get the basic strong understanding of how to preprocess and build a model based on your data by visulizing it with various
   tools
<br>
<br>
Libraries used:<br>
scikit learn,pandas,matplotlib,numpy,seaborn

<br>
=> Happy learning :)  