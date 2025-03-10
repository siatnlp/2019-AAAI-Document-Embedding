# 2019-AAAI-Document-Embedding
Learning Document Embeddings with Crossword Prediction

## Abstract
In this paper, we propose a Document Embedding Network (DEN) to learn document embeddings in an unsupervised manner. Our model uses the encoder-decoder architecture as its backbone, which tries to reconstruct the input document from an encoded document embedding. Unlike the standard decoder for text reconstruction, we randomly block some words in the input document, and use the incomplete context information and the encoded document embedding to predict the blocked words in the document, inspired by the crossword game. Thus, our decoder can keep the balance between the known and unknown information, and consider both global and partial information when decoding the missing words. We evaluate the learned document embeddings on two tasks: document classification and document retrieval. The experimental results show that our model substantially outperforms the compared methods.
