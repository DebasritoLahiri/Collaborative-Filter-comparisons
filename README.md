# Collaborative-Filter-comparisons
Does a comparison of performance of Model based and Memory based collaborative filters. Uses Matrix Factorization using SVD for Model based and KNN with Cosine similarity for Memory based.

Dependencies:
1. Surprise Library(Made from Scikit-learn)(Contains the ml models, cross validation tools, metrics tools, dataset etc.)
2. Pandas
3. Numpy
4. Random library
5. Pathlib

The dataset used is  ml-100K provided by GroupLens tm. Surprise library has this dataset inbuilt in it and it is imported from there. However, it is also provided separately if needed.

To install surprise library run the follwing command in anaconda powershell prompt:
conda install -c conda-forge scikit-surprise
