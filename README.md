# BERT-Fake-News-Classifier
The goal of this project is a binary classification task for fake news detection. Incorporation of pre-trained BERT and a forward feed neural network construct the classifier. After fine-tuning the classifier with 10000 balanced records of fake and real news data, the accuracy of 92% is achieved.

# Running the project

To execute the Python notebook, you need to include the CSV files in the Dataset folder in the execution path.

# Bidirectional Encoder Representation Trans-formers (BERT)

BERT is a new language model introduced by Google Brains in 2018. This pre-training Language model is developed based on the attention mechanism. Attention is simply the contextual relations in a text sequence. Before introducing Transformers, the attention was obtained using RNNs like GRU or LSTMs, but this process was usually computationally intensive and incomplete.
The advent of Transformers brought about the capability of complete attention extraction in text sequence and parallel computation on GPUs.

BERT is also a transformer designed to obtain all attention in a text sequence. Its architecture is comprised of encoders and a set of self-attention heads. BERT aims to carry out two tasks: Language model and next sequence prediction.
Pre-trained BERT models are introduced in several volumes and adjusted variables for the tasks mentioned above in different Languages. These pre-trained models should be fine-tuned with a shallow or deep learning classifier for specific tasks like Fake news detection.


# Dataset 
The chosen dataset for this project is : 

    https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset

# References 

    1. https://towardsdatascience.com/text-classification-with-bert-in-pytorch-887965e5820f
    2. https://towardsdatascience.com/fake-news-classification-with-bert-afbeee601f41
    3. Devlin, Jacob, et al. "Bert: Pre-training of deep bidirectional transformers for language understanding." arXiv pre-print arXiv:1810.04805 (2018).
