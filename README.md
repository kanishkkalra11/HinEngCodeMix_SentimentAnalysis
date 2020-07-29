# HinEngCodeMix_SentimentAnalysis

The project is to build a classifier for sentiment analysis of Hindi-English Cide Mix tweets.

Before running the model, make sure to install all the equirements. You can do this by:
pip install -r requirements.txt

The dataset as well as the processed data has been provided in the directory "Dataset". Additionally, the code for preprocessing of the raw data has also been provided in the notebook.

The model can be trained and evaluated using the notebook model_train_and_evaluate. It is based on fine tuning on the pre-trained Bert Base-Uncased model. The model has been implemented using ktrain which is a lightweight wrapper for keras and allows for quixk and easy working with neural netwroks. More useful information about how to use ktrain can be found [here](https://github.com/amaiya/ktrain).

A 57% accuracy has been obtained on the test data with F1 scores for classes positive, negative and neural being 0.59, 0.59 and 0.54 respectively.
