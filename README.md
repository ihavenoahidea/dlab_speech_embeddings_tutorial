# Generating embeddings from a self-supervised speech model

Supplement to the UC Berkeley DLab blog post.

This tutorial covers how to generate audio embeddings using self-supervised speech models. Like their more famous cousins, large language models, self-supervised speech models are transformer-based deep learning models. Unlike LLMs, which are trained on text, speech models are trained on speech. They convert audio data into embeddings, which are rich representations of the underlying audio that can be used for speech recognition, speaker identification, and linguistic research. The tutorial is aimed at those who would like to experiment with speech embeddings, but who may not have an extensive background in PyTorch or the `transformers` library.
