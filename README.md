# Multi-Label-Text-Classification-using-RNN
RNN works on the principle of saving the output of a particular layer and feeding this back to the input in order to predict the output of the layer.
The nodes in different layers of the neural network are compressed to form a single layer of recurrent neural networks. A, B, and C are the parameters of the network.




![Network_framework](https://user-images.githubusercontent.com/79834087/172401648-abd74405-a3bb-4797-93a0-33870dc31fff.gif)

Here, “x” is the input layer, “h” is the hidden layer, and “y” is the output layer. A, B, and C are the network parameters used to improve the output of the model. At any given time t, the current input is a combination of input at x(t) and x(t-1). The output at any given time is fetched back to the network to improve on the output!

[Fully_connected_Recurrent_Neural_Network1](https://user-images.githubusercontent.com/79834087/172402431-9290467f-60cc-4abf-bb1e-f5aeb364b1ca.png)

RNN were created because there were a few issues in the feed-forward neural network:

Cannot handle sequential data
Considers only the current input
Cannot memorize previous inputs
The solution to these issues is the RNN. An RNN can handle sequential data, accepting the current input data, and previously received inputs. RNNs can memorize previous inputs due to their internal memory.
