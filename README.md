# Reading Comprehension with SQuAD 2.0

This project explores extractive question answering with the SQuAD 2.0 dataset using TensorFlow, Keras, and BERT.

## Notebooks

- **`custom_encoder.ipynb`**: Loads and analyzes SQuAD 2.0, including answerability, text statistics, and answer alignment.
- **`bert-squad.ipynb`**: Preprocesses the dataset and trains a BERT-based question-answering model.

## Getting Started

Install the required packages, then run the notebooks in the order listed above:

```bash
pip install tensorflow keras keras-hub transformers datasets pandas numpy matplotlib seaborn
```

The notebooks download the SQuAD 2.0 dataset and the required BERT tokenizer automatically.
