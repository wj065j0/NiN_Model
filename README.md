# NiN_Model

### Model
- Consist of 3 stacked mlpconv layers
- Followed by max pooling layer
- Dropout is applied on the outputs of all
but the last mlpconv layers
- All the networks used global average pooling
instead of fully connected layers

### Hyperparameter
- Batch Size: 128

## NIN Model Training

### Environment
- Google Colab
### Framework
- Tensorflow Keras
### Dataset
- CIFAR-10

## Reference
- [NETWORK IN NETWORK](https://arxiv.org/pdf/1312.4400.pdf) </br>
- [NETWORK-IN-NETWORK IMPLEMENTATION USING TENSORFLOW](https://embedai.wordpress.com/2017/07/23/network-in-network-implementation-using-tensorflow/)
