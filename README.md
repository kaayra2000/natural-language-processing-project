# Natural Language Processing Project

## What Does It Include

* ChatBot

** chatgui.py

This code snippet is a part of a chatbot that processes user input and returns a predicted response. First, the NLTK library is used to lemmatize the words in the sentence and then a bag of words is created for those words. Then, using the loaded model, the class of the sentence is predicted and the results are returned, as long as they fall below a certain threshold. The class with the highest probability is selected and as a response, an associated response from that class is chosen.

** train_chatbot.py

This code snippet is a part of a chatbot that uses a deep learning model to classify user input and return an appropriate response. It starts by loading a JSON file containing a list of `intents`, which are a combination of patterns of user input and corresponding responses. Then, it uses the NLTK library to tokenize the patterns of user input and to lemmatize the words. Then it creates a bag of words representation of the input and it creates a list of classes, which are the tags corresponding to the intents. It then removes duplicates, sorts the words and classes and saves them to a pickle file for later use. Finally, it creates a training dataset for the model by creating a bag of words representation for each input-output pair. Then it is ready to use this dataset to train a deep learning model like an ANN (Artificial Neural Network) with keras.

* Regular Expression

In the given assignment, REGEX is used to extract address blocks from the address data.
