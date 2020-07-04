# CC2Vec: Distributed Representations of Code Changes [[pdf](https://arxiv.org/pdf/2003.05620.pdf)]

## Implementation Environment

Please install the neccessary libraries before running our tool:

- python==3.6.9
- torch==1.2.0
- tqdm==4.46.1
- nltk==3.4.5
- numpy==1.16.5
- scikit-learn==0.22.1

## Hyperparameters:
----------------
We have a number of different parameters:

* --embedding_dim: Dimension of embedding vectors.
* --filter_sizes: Sizes of filters used by the hierarchical attention layers. 
* --num_filters: Number of filters. 
* --hidden_layers: Number of hidden layers. 
* --dropout_keep_prob: Dropout for training cc2vec. 
* --l2_reg_lambda: Regularization rate. 
* --learning_rate: Learning rate. 
* --batch_size: Batch size. 
* --num_epochs: Number of epochs. 

## Contact

Questions and discussion are welcome: vdthoang.2016@smu.edu.sg