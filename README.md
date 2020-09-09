# Fake-News-Detection
Deep Neural Network using word embedding to detecting stances
The probelm is organized around the more well-defined problem of “stance detection,” which involves comparing a headline with a body of text from a news article to determine what relationship (if any) exists between the two.  
# There are 4 possible classifications:  
1.The article text agrees with the headline.  
2.The article text disagrees with the headline.  
3.The article text is a discussion of the headline, without taking a position on it.
4.The article text is unrelated to the headline (i.e. it doesn’t address the same topic). 
# Procedure:
Step 1: Cconvert words into vectors and make them ready for the model.
Step 2: Build Sequential Models like RNN, LSTM in Keras.
Step 3: Train the model and check the accuracy

One can also use Callbacks to improve learning speed.
Use of Attention model to see if the model accuracy can be improved.
