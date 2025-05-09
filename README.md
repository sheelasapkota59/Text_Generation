# Text_Generation
This is a beginner-friendly Natural Language Processing (NLP) project where I implemented a basic text generation model using LSTM (Long Short-Term Memory) networks in TensorFlow/Keras. The goal is to generate new words based on a given seed text, trained on a small sample dataset. The project helped me understand the text preprocessing pipeline, sequential modeling, and how sequence-to-sequence prediction works using deep learning.
Objective:
To build a model that can:
Learn from a small sample of text
Predict the next possible word(s) based on a given seed sentence
Generate meaningful or pattern-following sequences (depending on training data)
Technologies Used
    Python
    NumPy & Pandas
    TensorFlow & Keras
    Natural Language Processing (Tokenization, Padding)
Model Architecture
    Tokenizer to convert text to sequences
    Padding to equalize input lengths
    Embedding Layer: Learns word vectors
    LSTM Layer: Captures temporal dependencies
    Dense Output Layer with softmax activation for multiclass prediction

Dataset
    Type: Manually provided sample string (can be replaced with any text corpus)
    Example: "The quick brown fox jumped over the lazy dog."
    
