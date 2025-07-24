# Python Chatbot

This is an intent-based chatbot built with Python using TFLearn and TensorFlow. It is designed to operate effectively within a defined scope and can be retrained for specific use cases. The chatbot relies on an `intents.json` file that defines its conversational patterns and responses.

Even if a user's input doesn't exactly match the trained patterns, the model can still predict the correct intent with high accuracy. It assigns probabilities to each possible intent (tag) and returns an appropriate response. Additionally, responses are spoken aloud using the `pyttsx3` text-to-speech library.

## To run:
Clone the repo to your local machine:
```
https://github.com/lance0145/python_chatbot.git
```
Install dependencies:
```
pip install -r requirements.txt
```
You can run ```main.py``` directly as model is already trained on some sample data. But you can change the scope of chatbot by updating ```intents.json``` file and then training the
model by running ```training_chatbot.ipynb```.