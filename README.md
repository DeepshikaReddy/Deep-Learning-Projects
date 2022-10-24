# Deep-Learning-Projects

1.NLP_Next_Word_Prediction:This exercise aims at feature engineering, understanding basic LSTM models and cheking the prediction values
## Featurization
### [BagOfWords,TF-IDF,Avg W2Vec,TF-IDF W2Vec]
### https://www.youtube.com/watch?v=PfXnKDPFFHo

### 1.Title : As title is a text field it can be featured using IDF Weighted Word2Vec as it performs better than avg W2Vec
### Word2Vec : tfidf doesnt preserve the similarity between the words , so this is used. It is a 2 layer neural network which gives the same vector value for similar sentences from the Corpus. It works based on CBOW or Skip gram.
### 2.Image vector :using CNN
<bold>Convulution layer</bold> multiples every pixel of target image with a small window pixel, then the <bold>relu</bold> converts all negetive number to positive in the array and <bold>pool layer</bold> basically shrinks the dimensions of the 2d array,<bold>full connected layer </bold>takes the maximum votes from diffrent arrays like 1 and near to 1 belong to ClassA , 0 and closer to 0 belong to ClassB.
### https://www.youtube.com/watch?v=FmpDIaiMIeA
### 3.Brand: CountVectorizer
### 4.Color: CountVectorizer
### https://www.youtube.com/watch?v=v_4KWmkwmsU
### https://www.youtube.com/watch?v=mHkdcA-zyYE
