# Assignment 8 — BERT Sentiment Analysis

This practical evaluates a pretrained BERT sentiment classifier on a sample of the SST-2 validation set. It reports accuracy, precision, recall, and F1 score; plots a confusion matrix; reviews misclassified sentences; and predicts the sentiment of a custom example. The notebook performs inference with an existing model rather than training a new one.

## Files

- `Prac8.ipynb` — runnable evaluation and inference notebook.
- `DL_Assignment-8_12414973.docx.docx` — practical implementation sheet with code and output. The doubled `.docx` extension is retained as supplied.

## Requirements

The notebook uses PyTorch, Hugging Face `transformers` and `datasets`, NumPy, pandas, Matplotlib, seaborn, and scikit-learn. It downloads `textattack/bert-base-uncased-SST-2` and the `nyu-mll/glue` SST-2 validation split, so an internet connection is needed on the first run.
