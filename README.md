# PyTorch RNNs

An implementation of RNN variants from scratch in Pytorch, to help understand RNNs.

Implemented RNNs:
- [LSTMCell](https://pytorch.org/docs/stable/nn.html#lstmcell)
- [LSTM](https://pytorch.org/docs/stable/nn.html#lstm)
- [GRUCell](https://pytorch.org/docs/stable/nn.html#grucell)
- [GRU](https://pytorch.org/docs/stable/nn.html#gru)

The implementations are tested on the [MNIST Dataset](http://yann.lecun.com/exdb/mnist/) for classification.

Each 28x28 MNIST image considered as sequences of a 28-dimensional input vector.

## Model:
- A recurrent neural network (LSTM or GRU)
- A fully connected layer that maps the 128-dimensional input to the 10-dimensional vector of class labels
