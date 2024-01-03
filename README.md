# Directory structure

### word similarity

This directory contains the code for training a model to predict word similarity scores given two input words, and evaluating the model on the simlex 999 dataset.

There are two subdirectories:

**************Part 1************** 

This subdirectory contains code for a model, present in the jupyter notebook **********************************constrained.ipynb**********************************, that was trained with the following constraints:

- any monolingual English corpus - Maximum 1 million tokens.
- any curated/structured knowledge-bases / ontologies

************Part 2************

This subdirectory contains code for a model, present in the jupyter notebook **********************************unconstrained.ipynb**********************************, that was trained without any constraints on data or pre-trained models.

### phrase similarity

This directory contains the following files:

**********************************************static_embeddings.ipynb**********************************************

The juptyer notebook contains code to train a model to perform phrase similarity classification, using pre-trained static embeddings.

**************************contextual_embeddings.ipynb**************************

The juptyer notebook contains code to train a model to perform phrase similarity classification, using contextual embeddings.

The directory also contains a folder ********************embeddings******************** that has the necessary files for the GloVe model used in the task.

### sentence similarity

This directory contains the following files:

**********static_embeddings.ipynb**********

The juptyer notebook contains code to train a model to perform sentence similarity classification, using pre-trained static embeddings.

******************************sentence_transformer.ipynb******************************

The juptyer notebook contains code to train a model to perform sentence similarity classification, using a pre-trained transformer based model to get sentence embeddings.

**********************************************************added_transformer_layer.ipynb**********************************************************

The juptyer notebook contains code to train a model to perform sentence similarity classification, using a pre-trained transformer based model to get sentence embeddings and an additional transformer layer which has been implemented from scratch to derive more meaning from the features.

The directory also contains a folder ********************embeddings******************** that has the necessary files for the GloVe model used in the task.