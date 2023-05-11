# Emoji Prediction


This project is an emoji prediction model built using natural language processing techniques and trained on a dataset of text messages and their corresponding emojis. The model uses the GloVe word embedding to represent words as vectors and a neural network to classify text messages into their corresponding emojis.

## Getting Started

### Prerequisites
- Python 3
- TensorFlow
- Keras
- NumPy
- NLTK
- Matplotlib
- Seaborn


## Files

- Emoji_Class.ipynb: A Jupyter Notebook containing the code for the emoji prediction model.
- glove.6B.50d.txt: A pre-trained word embedding file used by the model to represent words as vectors.
- test_emoji.csv: A CSV file containing test data for the model.
- train_emoji.csv: A CSV file containing training data for the model.

## How to use

1. Clone this repository: ``` git clone https://github.com/your-username/emoji-prediction.git ```
2. Install the necessary libraries: ``` pip install -r requirements.txt ```
3. Open `Emoji_Class.ipynb` in Jupyter Notebook.
4. Run the cells in the notebook to train and test the model.
Dataset

The dataset used in this project is a collection of text messages and their corresponding emojis. It consists of two CSV files:

- train_emoji.csv: Contains 132 text messages and their corresponding emojis for training the model.
- test_emoji.csv: Contains 56 text messages and their corresponding emojis for testing the model.
## Acknowledgements

This project was inspired by the Emoji Predictor by Neel Shah. The dataset used in this project was taken from his repository. The pre-trained word embedding file used in this project was created by the Stanford Natural Language Processing Group and can be downloaded from their website.