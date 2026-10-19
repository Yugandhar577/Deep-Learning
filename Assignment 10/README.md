# Assignment 10 — Audio Classification, STT, and TTS

This practical builds an eight-class speech-command classifier using log-mel spectrograms and a CNN. It also uses a pretrained Whisper model for speech-to-text (STT) and a pretrained MMS model for text-to-speech (TTS). The report evaluates the classifier with accuracy and class-level metrics and measures transcription errors for STT.

## Files

- `DL_Assignment-10_12414973.docx` — practical implementation sheet containing the code, evaluation, and results.

There is currently no separate notebook in this folder. The report's code is written for Google Colab paths under `/content/`. It downloads the Mini Speech Commands dataset and pretrained speech models. Main dependencies include PyTorch, torchvision, Transformers, librosa, soundfile, jiwer, scikit-learn, pandas, Matplotlib, and tqdm.
