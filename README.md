# sco-boscmf
Sense co-occurrence and bag of sences context matrix factorization

Author: Hussein AL-NATSHEH <hussein.al-natsheh@ish-lyon.cnrs.fr>.

Affiliation: EA 3083 - University of Lyon, USR 3385 - CNRS, France.

License: BSD 3 clause 2016

# Dependencies:
#Make sure you have gcc installed:
sudo apt-get install build-essential

# Install glove-python
https://github.com/natsheh/glove-python .

python glove-python/setup.py install

# Install SpaCy:
export LC_ALL=C \n
pip install spacy \n
python -m spacy.en.download

This library helps you in building a co-occurrence matrix of senses (tagged word, e.g. Apple_inc|ORG) extracted from a text corpus like Wikipedia. It also allows you to build context (i.e. sentence, paragraph or document) bag of senses. These matrices would be then transformed and factorized in order to have distributional representation of the senses and/or the contexts.

The project is under development for research purposes
# Keywords
Natural Language Processing; Machine Learning; Matrix Factorization; Dictionary Learning; Features Reduction
