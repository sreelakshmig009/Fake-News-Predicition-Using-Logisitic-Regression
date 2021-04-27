# Fake-News-Predicition-Using-Logisitic-Regression
 Python3,Logistic Regression,Executed on Google-Colab 

Check out this awesome youtube channel to learn Machine learning : https://www.youtube.com/channel/UCG04dVOTmbRYPY1wvshBVDQ

1.Logistic regression model
2.Binary model:fake news,real news(for binary models,logistic regression gives the most accurate ouput)

Work Flow
1.News data
2.Data Pre-Processing(labelling and converting into csv files)
3.Train Test Split
4.LR model
5.Training

After training the model,when we feed input it should say whether it is a real news or fake news

Important Terms seen across the code along with their definitions:


Stemming:  Removes the prefix and suffix of a word and returns the root word(along with stopwords)
Stemming is the process of reducing a given word to its root word. This is an important process because we need to reduce the input size as much as we can for a faster and efficient output
Train_test_data to split into training and test data

Stopwords : words that doesnt add value to news/context of data(articles)
vectorizing : Convert the stemmed words into their equivalent numerical values(tfidfvector text into feature vectors)
accuracy_score tells how much accurate is the news

Learn about PorterStemmer here: https://www.tutorialspoint.com/python_data_science/python_stemming_and_lemmatization.htm

TfidVectorizer : tf- Term Frequency
                 idf-  Inverse document frequency
Stratify in train_test_split : used to segregate data into equal proportions the same way it was in the original pre-trained dataset


Math behind Logisitic Regression: 
                                            Sigmoid function
                                            y = 1/1+e^(-z) 
                                             z = w.X + b - straight line equation
                    where,
                                   X = input features 
                                   Y = prediction probability(b/w 0 and 1)
                                   w = weights(how important a particular feature/column is)
                                   b = biases
