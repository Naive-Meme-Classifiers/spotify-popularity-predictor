# spotify-popularity-predictor
 
 Predicting the popularity of songs on Spotify with machine learning.
 
 ## Overview
 
 This repo contains Jupyter notebooks with the results of three ML models trained to predict the popularity of songs using the [Spotify Web API](https://developer.spotify.com/documentation/web-api/reference/#reference-index). The models we trained were a decision tree, support vector machine, and multilayer perceptron.
 
 ## Files
 
 - `data.csv` - The dataset obtained from [Kaggle](https://www.kaggle.com/yamaerenay/spotify-dataset-19212020-160k-tracks) in January 2021.
 - `predictor-dt.ipynb` - A Jupyter notebook for the decision tree.
 - `predictor-svm.ipynb` - A Jupyter notebook for the support vector machine.
 - `predictor-mlp.ipynb` - A Jupyter notebook for the multilayer perceptron.
 
 ## Dependencies
 - `imbalanced-learn`
 - `matplotlib`
 - `pandas`
 - `scipy`
 - `seaborn`
 - `shap`
 - `sklearn` 
 - Anaconda was used to run the notebooks, which includes several more dependencies that may also be required implicitly.
