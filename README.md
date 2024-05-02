

# Caera Chatbot

Caera Chatbot is a simple conversational AI model trained on predefined intents to engage in text-based conversations with users. It utilizes a neural network model trained on a dataset containing intents and their corresponding responses. The model predicts the appropriate response based on the user input.

## Features

- **Conversational Interface**: Engage in text-based conversations with Caera.
- **Predefined Intents**: Recognizes predefined intents and responds accordingly.
- **Customizable**: Easily add new intents and responses to customize the chatbot.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your_username/Caera-Chatbot.git
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Download the pre-trained model files (model, tokenizer, label encoder) and place them in the project directory.

4. Run the chatbot:

    ```bash
    python chatbot.py
    ```

## Usage

1. Start the chatbot by running the `chatbot.py` script.
2. Type your message in the console and press Enter.
3. Caera will respond with an appropriate message based on the input.

## Dataset

The training data for the chatbot is stored in the `indents.json` file. It contains intents and their corresponding patterns and responses.

## Customization

You can customize the chatbot by modifying the training data in the `indents.json` file. Add new intents, patterns, and responses to teach Caera new skills.

