# Generation of music using neural networks

## Bachelor thesis

This thesis aims at using artificial neural networks in machine music generation.
We emphasized using natural language processing techniques based on attention mechanisms.
The work describes the whole music generation pipeline from data selection through *tokenization* (transforming music from raw data into a format digestible by selected models) up to model training.

We used state-of-the-art models based on the *Transformer* and the *LSTM* architectures commonly used in NLP to answer whether these well-performing models in domains like text generation or text translation can also be used to generate music.
We also tested some proposed enhancements to the Transformer model and the attention mechanism and compared them to the vanilla Transformer model.

We used the MAESTRO and the GiantMIDI datasets for the training process that contain hundreds of hours of classical piano pieces.
The songs used for training the models are in symbolic MIDI representation.