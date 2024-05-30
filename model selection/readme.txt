-> check the distribution of independent variables
-> rescaling the normal data ( attributes with normal dist) with standardscaler
-> remaining attributes rescaled with minmaxsclaer
-> Applied kcrossvalidation with model( kneighbourregressor)
-> kcrossvalidation(n_splits=3):
       divide the whole data into 3 partitions and two are used for train and other one is for test
       then after first and third partition are used for train and second part is for test
       it is repeated until each part is selected as test by calclulationg the error at each step 
       and taking the mean at final
-> we got 1.21 mean absolute error for k = 5 i.e n_neighbors

=> go through the /temp_m.ipynb for clear implementation