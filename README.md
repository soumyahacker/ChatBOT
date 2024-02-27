# ChatBot using TensorFlow and Natural Language Processing

## Overview
This repository contains the code for a simple chatbot built using TensorFlow and Natural Language Processing (NLP) techniques. The chatbot is trained to understand user queries, predict intents, and generate appropriate responses.

## Features
- **Data Preparation:** The model is trained on a dataset with predefined patterns and intents, allowing it to recognize user input.
- **Neural Network:** A neural network is implemented using TensorFlow's Keras API for intent prediction.
- **User Interaction:** Users can interact with the chatbot through the command line, receiving responses based on predicted intents.
- **Model Persistence:** The trained model is saved to enable easy deployment and reuse.

## Setup
1. Install required libraries: `pip install -r requirements.txt`
2. Run `python data_preparation.py` to preprocess the training data
3. Interact with the chatbot using `python chatbot_interactive.py`.

## Files
- **data_preparation.py:** Preprocesses the training data and saves necessary information (words, classes) using pickle.
- **neural_network.py:** Builds, compiles, and trains the neural network using TensorFlow.
- **chatbot_interactive.py:** Allows users to interact with the trained chatbot model through the command line.
- **intents.json:** Contains predefined patterns and responses for various intents.
- **words.pkl and classes.pkl:** Pickle files storing processed words and classes for model input.
- **chatBot_Model.h5:** The saved trained model.

## Usage
1. Run `chatbot_interactive.py`.
2. Enter messages to engage in a conversation with the chatbot.
3. Type 'quit' to exit the conversation.

## Author
- Soumyapriya Goswami (GitHub: [soumyahacker](https://github.com/soumyahacker))

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Feel free to contribute, report issues, or use this project as a starting point for your chatbot development endeavors!
