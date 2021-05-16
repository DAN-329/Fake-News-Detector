# Fake-News-Detector

A Fake News Detector created using a LSTM (Long short-term memory) neural network to differentiate between real and fake news titles.

To do this we use two datasets Fake.csv holding fake news articles and True.csv holding true news articles and apply initial data preprocessing to remove unnecessary columns following which we combine and jumble them to form a single dataframe.

Then we perform stemming and remove stopwords from the titles while also performing one-hot encoding and embedding.

We then create the model, train it and finally perform metrics and accuracy to test it.

*A “requirements.txt” file has also been provided for installation of necessary packages.*
