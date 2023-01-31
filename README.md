# CACL

Usage
Below are examples of how to run CACL.
python -u train_CACL.py \
--data_path ./reviews.json \
--cuda 1
--rnn_dropout >> 0.8
--factor >> 1.0
python -u test_CACL.py \
--data_path ./reviews.json \
--cuda 1
--rnn_dropout >> 0.8
--factor >> 1.0

Code dependencies
Python== 3.7
PyTorch ==1.12.1
transformers==4.25.1
pandas==1.4.3
mkl-service==2.4.0
nltk==3.7
tokenizers==0.13.2
ply==3.11


TensorFlow implementation of model 
train_CACL.py is used for train a model.
test_CACL.py is generate text.
utilities.py has functions for processing input files.
CACL.py  contains the specific steps of the model.
