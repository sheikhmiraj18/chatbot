# College Chatbot

Developed an AI-powered chatbot designed to assist users with queries related to IIT Guwahati. The chatbot provides information on various topics such as admission processes, course offerings, campus life, facilities, events, and more.

Key Features:

- Natural Language Processing (NLP): Utilized NLTK for tokenization and stemming to preprocess user inputs.
- Machine Learning: Implemented a neural network model using TensorFlow and TFLearn to classify and respond to user queries based on predefined intents.
- Data Handling: Parsed and managed training data from JSON files, and used pickle for saving and loading processed data.
- Interactive Interface: Developed an interactive command-line interface allowing users to chat with the bot and receive instant responses.

## Installation

### Create an Environment

We have to use Python 3.6 for this.

```console
conda create -n chatbot python=3.6
```

### Activate it

```console
activate chatbot
```

### Install PyTorch and dependencies

```console
pip install torch
pip install nltk
pip install numpy
pip install numpy
pip install tflearn
pip install tensorflow
```

## Usage

### To run the chatbot, simply run the file

```console
python main.py
```
