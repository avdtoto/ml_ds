# Yes/No Question Answering with BoolQ

This project implements a yes/no question-answering system using the BoolQ dataset from the SuperGLUE benchmark. BoolQ is a dataset designed for yes/no questions, where each sample contains a question, a passage providing context, and the correct answer ("yes" or "no"). The goal of this project is to explore various models and techniques to solve the yes/no question-answering task efficiently.

## Project Overview

The project investigates both traditional machine learning classifiers and modern approaches like BERT embeddings and fine-tuning to perform the question-answering task. By comparing these approaches, the project seeks to identify the most effective method for achieving high accuracy in answering yes/no questions.

## Installation and Requirements

To run this project, you will need the following dependencies:

- Python 3.x
- Jupyter Notebook
- TensorFlow or PyTorch
- Hugging Face Transformers library
- Scikit-learn
- Pandas
- NumPy
- Matplotlib (for data visualization)

You can install the dependencies using pip:

```bash
pip install torch transformers scikit-learn pandas numpy matplotlib

