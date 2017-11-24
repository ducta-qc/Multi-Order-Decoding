# Multi-Order-Decoding
This is an implementation of the paper [Does Higher Order LSTM Have Better Accuracy in Chunking and Named Entity Recognition?]

## Environment and Dependency
- Ubuntu 16.04
- Python 2.7
- Tensorflow 1.0 

<br /> 
## Required Files

#### Feature files
The model uses features extracted from original texts. Ignore the feature input in the model if you don't want to use extracted features.

#### Probability Files
The model uses features extracted from original texts. Ignore the feature input in the model if you don't want to use extracted features.
The order-3 LSTM-MOD model uses the probabilities generated by naive order-1 model and naive order-2 model at testing stage. So the probabilities need to be preserved in files. We provide probability files generated in our experiments. You can also get the files by training your own naive order-n models. The naive order-n model is exactly bi-directional lstm with order-n tag set.
