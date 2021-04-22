# Movie-Recommender

Installation

Install Jupyter notebook, Python and the following necessary packages.

Jupyter: https://jupyter.org/install

Python: https://www.python.org/downloads/

Numpy: https://anaconda.org/anaconda/numpy

Sklearn: https://anaconda.org/anaconda/scikit-learn

Pandas: https://anaconda.org/anaconda/pandas

Pickle: https://anaconda.org/conda-forge/pickle5

Joblib: https://anaconda.org/anaconda/joblib

Folder information

The submission folder contains six .ipynb files, a datasets folder and a model folder. The datasets folder contains the results saved from different steps in the whole pipeline of the solution including .csv files and .pkl files. It should also contain the original dataset ratings.csv from MovieLens 25M dataset and sampled_ratings.csv which could not be uploaded due to its size. The model folder contains .joblib files for regression models.

Running the Project

If you want to use the stored files and models:

i.	For movie recommendation: Open MovieRecommendation.ipynb using Jupyter notebook and run each cell. After running the whole file, the output of the last cell will provide the recommendations for a randomly selected user.

ii.	For movie rating prediction: Open MovieRatingPrediction.ipynb using Jupyter notebook and run each cell. After running the whole file, the output of the last three cells will provide the recommendations for a randomly selected user and a movie. Based on the evaluation metric, we can use the outputs for linear or ridge model as the final rating prediction.

If you want to start everything from scratch. 

Delete everything from the datasets folder except for the original MovieLens datasets movies.csv and ratings.csv.
Run the following files in the given order. These files also contain comments if there’s anything that should be done.

i.	Preprocessing.ipynb

ii.	ClusteringUsers.ipynb

iii.	MovieRecommendation.ipynb

iv.	EncodeGenres.ipynb

v.	PredictionModel.ipynb

vi.	MovieRatingPrediction.ipynb

References:

1.	https://realpython.com/k-means-clustering-python/#understanding-the-k-means-algorithm
2.	https://github.com/asdkazmi/AI-Movies-Recommendation-System-K-Means-Clustering
3.	https://github.com/gauravtheP/Netflix-Movie-Recommendation-System/blob/master/NetflixMoviesRecommendation.ipynb
4.	https://scikit-learn.org/stable/modules/clustering.html
5.	https://scikit-learn.org/stable/modules/linear_model.html
