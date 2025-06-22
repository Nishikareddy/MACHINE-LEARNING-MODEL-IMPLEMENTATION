MACHINE LEARNING MODEL IMPLEMENTATION

NAME:Gaddam NISHIKA REDDY

INTERN ID: CT04DN1601

DOMAIN: PYTHON PROGRAMMINGN

DURATION: 4 WEEKS 

MENTOR: NEELA SANTHU

DESCRIPTION: This project is a machine learning-based SMS spam classifier built using Python. It uses a dataset of SMS messages to train a model that can detect whether a message is spam or not. The dataset, called the SMS Spam Collection, is loaded from a public link and contains two columns: the message itself and its label—either ‘ham’ (not spam) or ‘spam’. First, the data is visualized using a bar chart to show the number of spam and non-spam messages, giving a quick idea of the dataset's balance. Next, the labels are converted into numeric values where 'ham' is mapped to 0 and 'spam' to 1 for machine learning purposes.

The dataset is then split into training and testing sets using train_test_split, so the model can be trained on one part of the data and tested on another to check how well it performs. The messages, which are in text form, are converted into a numerical format using a technique called Bag of Words through CountVectorizer. This step is necessary because machine learning models can't understand raw text directly—they need numerical data.

A Multinomial Naive Bayes classifier, which is well-suited for text classification tasks, is trained on the transformed training data. After training, the model is used to predict whether the messages in the test set are spam or not. The performance of the model is then measured using accuracy, a classification report, and a confusion matrix, which gives a clear visual representation of how many messages were correctly and incorrectly classified.

Finally, the model is tested with a sample custom message like “You've won a free iPhone! Claim it now!”, and it correctly predicts whether it's spam or ham based on what it learned during training. This project is a great example of how machine learning and natural language processing can be combined to solve real-world problems like spam detection. It's simple to understand and implement but powerful enough to demonstrate key machine learning concepts such as data preprocessing, model training, evaluation, and making predictions.
