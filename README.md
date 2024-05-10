**LSTM USING PYTORCH**\
This is a Fake News classifier created using LSTM model. The various tools that are implemented are Pandas, Python, Pytorch, NLTK.\
The vocab size for this project was set to 10,000 and each word or token was embedded in 100 dimensions creating a "lookup" or embedding table of 10000 * 100. The other tokens that weren't included in the vocabulary were assigned a special index and padded with zeros with the help of PyTorch before passing to the LSTM model to avoid errors.\
