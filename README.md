Sentiment-Analysis-Sklearn
Sentiment Analysis with SVM from Sklearn

(Click "Open in Kaggle" in the ipynb file to fully explore the project on Kaggle, as it comes with the dataset also.)

# Dataset
- The dataset used is the "amazon_review_polarity_csv.tar.gz" file from Xiang Zhang's Google Drive folder: https://drive.google.com/drive/folders/0Bz8a_Dbh9Qhbfll6bVpmNUtUcFdjYmF2SEpmZUZUcVNiMUw1TWN6RDV3a0JHT3kxLVhVR2M

- The file includes a test set and a training set. Only 10000 rows of the training set were used to train.

# Exploratory Data Analysis
We plotted the top words (1-gram), and 2-grams, and found that the most frequent words were "the", "and". This means filtering stop words from the dataset was necessary.

# Model
We loaded an SVM model with linear kernel of Scikit-learn library, and train it with 10000 rows of the train set. We ran the model through the whole test set and got an accuracy of 81%.

# Credits
- Dataset: https://drive.google.com/drive/folders/0Bz8a_Dbh9Qhbfll6bVpmNUtUcFdjYmF2SEpmZUZUcVNiMUw1TWN6RDV3a0JHT3kxLVhVR2M
- https://towardsdatascience.com/a-complete-exploratory-data-analysis-and-visualization-for-text-data-29fb1b96fb6a
- Teammates: Bui Quoc Minh Nhat
