# Natural Language Understanding - Assignment 2

**Author:** Neeraj Mansingh  
**Roll Number:** B23CS1095  

## Overview
This repository contains the source code and implementations for Assignment 2 of the Natural Language Understanding (NLU) course. The project is divided into two main tasks:
1. **Word Embeddings (Q1):** Custom web scraping of the IIT Jodhpur text corpus, building and training Word2Vec models (CBOW and Skip-gram) from scratch, evaluating semantic analogies, and visualizing the embeddings using t-SNE.
2. **Character-Level Language Modeling (Q2):** Curating a dataset of unique Indian names and training various recurrent neural network architectures (Vanilla RNN, BiLSTM, and Attention+RNN) to generate novel sequences autoregressively.

## Files in this Repository
* `B23CS1095_A2_Q1_NLU.ipynb`: The Jupyter Notebook containing the implementation for Question 1.
* `B23CS1095_A2_Q2_NLU.ipynb`: The Jupyter Notebook containing the implementation for Question 2.
* *(Note: Any required datasets, such as `corpus.txt` or `Training Names.txt`, are generated or fetched automatically by the code during execution).*

## How to Run the Code
The notebooks are entirely self-contained. All necessary libraries, web scraping tasks, dataset fetching, and model training will execute automatically.

1. **Download the Notebooks:** Download the `.ipynb` files from this repository to your local machine.
2. **Set up the Environment:** * **Option A (Recommended):** Upload the notebooks to [Google Colab](https://colab.research.google.com/). Ensure the hardware accelerator is set to GPU (T4) for faster training.
   * **Option B:** Open the notebooks in a local Jupyter Notebook/JupyterLab environment.
3. **Execute:** Open the notebook and simply click **"Run All"** (or `Runtime > Run all` in Colab). 
4. **Output:** The scripts will sequentially install dependencies, fetch the required text data, train the models, and print all quantitative metrics and qualitative outputs directly within the notebook cells.
