# Assignment 9 — Vision Transformer vs CNN

This practical compares image classification on CIFAR-10 using two pretrained feature extractors: a Vision Transformer (ViT-B/16) and a ResNet18 CNN. The report freezes each backbone, trains a linear classification head, and compares accuracy, macro precision, recall, F1 score, training time, inference speed, and parameter count.

## Files

- `DL_Assignment-9_12414973.docx` — practical implementation sheet with code, evaluation, and results.
- `Assignment_9.ipynb` — executable CIFAR-10 model-comparison notebook.

The notebook uses PyTorch/torchvision, NumPy, pandas, Matplotlib, scikit-learn, and tqdm. CIFAR-10 and pretrained model weights are downloaded when the code runs.
