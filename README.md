# Scientific peer reviews recommendation score prediction and Yelp reviews score prediction

There are three notebooks:

* **first_experiment.ipynb**: the multi-class classification work using PeerRead dataset and SVM. The pre-processing data steps also included. The cleaned and pre-processed datasets (train, test) can be found under *./datasets/exp1/* directory.

* **second_experiment_peerread.ipynb**: the multi-class classification work using PeerRead dataset and LSTM. The dataset (*./datasets/exp2/peer-reviews.csv*) is already cleaned following techniques in the first notebook and is ready to use.

* **second_experiment_yelp.ipynb**: the multi-class classification work using Yelp dataset and LSTM. The dataset (*./datasets/exp2/yelp_df_100k.csv*) is already cleaned following techniques in the first notebook and is ready to use. It contains 100k samples (reviews) only. 

* **second_experiment_binary.ipynb**: the binary classification work using Yelp dataset and LSTM. The same dataset (cleaned) is used like in *second_experiment_yelp.ipynb*. But it is further pre-processed to get samples labeled as positive and negative only (classes 0 and 1).




Dependencies:

*python (version 3.6)

*pytorch (version 0.4.1)

*torchtext (version 0.3.1)

*scikit-learn (version 0.20.1)

*spacy (version 2.0.13)

*numpy (version 1.15.3)

*pandas (version 0.20.3)

*nltk (version 3.2.2)

*seaborn (version 0.7.1)
