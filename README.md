# DeepTingle
Deep NN to generate stories to tingle your butt.

This repo contains all the code required to train DeepTingle or a similar system.
This repo consists of the following:
- **GloveData:** contains the trained GloVe word embedding over all chuck tingle stories using different sizes (50, 100, 200, 300)
- **Stories:** contains all chuck tingle stories in text files instead of PDFs.
- **website:** contains the files for the website.
- **DeepTingle Alphabet.ipynb:** is a python notebook used to train and test the alphabet based neural network model.
- **DeepTingle Words.ipynb:** is a python notebook used to train and test the word based neural network model.
- **Download Data and Unzip it.ipynb:** is a python notebook helper file to transfer files from GitHub and other sources to our computational machines.
- **From Glove to Words.ipynb:** is a python notebook experiment to train a simple neural network to reverse the GloVe embedding.
- **Preprocessing.ipynb:** is a python notebook used in preprocessing all chuck tingle files to be easier in training.
- **Testing & Experimenting.ipynb:** is a python notebook used in testing different ideas before adding it to the main code.

The core file is **DeepTingle Words.ipynb**. This code is used to train the current neural network used in the website. It contains all the different experiments used in the published paper. 

If you are looking for trained models here is the link:
- **Alphabet Based Model Weights:** http://www.deeptingle.net/deeptingleweights/CharacterBased.hdf5
- **Word Based Model Weights:** http://www.deeptingle.net/deeptingleweights/WordBased.hdf5

For more details about how it works check the ICCC 2017 paper: http://www.deeptingle.net/documents/iccc2017.pdf
