# Hierachical-Attention-Network
This is an implementation of the paper [Hierarchical Attention Networks for Document Classification](https://www.cs.cmu.edu/~./hovy/papers/16HLT-hierarchical-attention-networks.pdf), NAACL 2016.
## Requirements
- Python 3
- [Glove pre-trained word embeddings](http://nlp.stanford.edu/data/glove.6B.zip)
```
wget http://nlp.stanford.edu/data/glove.6B.zip
unzip glove.6B.zip`
```
`
pip install -r requirements.txt
`
## Dataset
- AG News
- DBpedia
- Yelp Review Polarity
- Yelp Review Full
- Yahoo Answers
- Amazon Review Full
- Amazon Review Polarity

These datasets could be download from [here](https://drive.google.com/drive/u/0/folders/0Bz8a_Dbh9Qhbfll6bVpmNUtUcFdjYmF2SEpmZUZUcVNiMUw1TWN6RDV3a0JHT3kxLVhVR2M?resourcekey=0-TLwzfR2O-D2aPitmn5o9VQ)
## How to run
Download datasets and unzip into a `Data` folder

`python data_prepare.py`

Training

`python train.py`
