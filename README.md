# Multi-Label-Text-Classification-using-RNN
A Recurrent Neural Network (RNN) is a type of neural network in which the output of the previous step is provided as the input of the current step. 
RNN is mainly used for sequence classification - sentiment classification and video classification. 
Sequence Tagging - Marks part of speech and identifies a named entity.
First the data set was divided into train set, validation set & test set. 
GloVe embedding is used to implement word embedding. Before word embedding data is Pre-processed.
Then the parameters are initialized which include input dimension, embedding dimension, hidden dimension, output dimensions and word embedding. 
RNN is a feed forward model output of one node is the input of the next node.
At first hidden start is set to all zeros.
Here we have mapped all the indexes present tin the input sequence of corresponding word vector using our trained word embedding. Then Applied RNN layer to start learning of the words.
Then at last linear layer applied to the output.
Model accuracy is measured using the Jaccard-Score and f1_score & hamming loss. Model is later saved to test it for the real world input and calculated the accuracy.
![1_0hkR4Bqiq1MN6Mew8E9t1w](https://user-images.githubusercontent.com/79834087/172398450-b781ca77-1349-41e9-b037-4c65ae4e72dd.png)
