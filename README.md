# Simple NLP Chatbot

## Overview
This Python script implements a basic chatbot using NLTK and spaCy for natural language processing. It identifies user intents and responds accordingly.

## Features
- Tokenizes and processes user input using NLTK and spaCy.
- Recognizes basic intents like greetings, farewells, and gratitude.
- Responds with predefined messages based on detected intent.
- Allows users to exit the chat by typing 'exit'.

## Requirements
Ensure you have the following dependencies installed:

```bash
pip install nltk spacy
python -m spacy download en_core_web_sm
```

## Usage
1. Run the script using Python:

```bash
python chatbot.py
```

2. The chatbot will start a conversation. Type a message and receive a response.
3. Type 'exit' to end the conversation.

## Expected Responses
- Greeting: "Hello! How can I assist you today?"
- Goodbye: "Goodbye! Have a great day!"
- Thanks: "You're welcome!"
- Default: "I'm not sure I understand. Can you rephrase that?"

## Customization
- Modify the `responses` dictionary to add or change responses.
- Extend the `get_intent` function to recognize more intents.

## License
This project is licensed under the MIT License.

