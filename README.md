# San-Summarizer

This repository contains codes for the training of the Extractive and Abstractive Text summarization models for Sanskrit text documents.  

We pre-trained the SOTA BERT (and its variants) models with our Sanskrit data and then fine-tuned these models for further usecases.  

For this project, we used these models for Extractive text summarization, we use the BERT (and its variants) embeddings for clustering and then find the most important sentences and give that as the summary.  

For the Abstractive Text summarization use-case, we use a hybrid pointer-generator network with BERT (and its variants) as the baseline-encoder and then add a decoder and a pointer-generator network on top to be able to handle OOV (Out-Of-Vocabulary) words and to tackle the problems of factual inaccuracies.  

The models and the data is not available to public yet. But will soon be out for further research.  

Checkout the San-BERT paper here : <strong>https://arxiv.org/abs/2304.01894</strong>.  

For any further queries, please mail at : *jammikunal000@gmail.com*  
