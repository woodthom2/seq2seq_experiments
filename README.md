# protein_ner
NER on protein texts

# Approaches

I'm using two approaches

* Conditional Random Fields (using CRFSuite)
* RNNs (using TensorFlow seq2seq)

# Requirements

* Python 2.7 (Anaconda recommended)
* TensorFlow 1.0
* (for training) a GPU e.g. NVIDIA 1080

# Getting started

* Choose a data directory and set as an environment variable RNN_HOME
* mkdir $RNN_HOME/raw and put the three files from the task in here
* mkdir $RNN_HOME/preprocessed
* mkdir $RNN_HOME/data
* mkdir $RNN_HOME/train 
* In folder rnn, execute Preprocess.ipynb. This will prepare the training data for a format that it can be used to train the RNN.
* In folder rnn, execute train_model.sh
* To execute the trained model, execute run_model.sh


