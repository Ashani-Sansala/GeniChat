# GeniChat - Chat with GPT-4o

Welcome to **GeniChat**, a Streamlit-based chatbot that interacts with OpenAI's GPT-4o model to provide conversational AI capabilities. This project is designed to demonstrate how to create a simple and interactive chat interface using Python, Streamlit, and the OpenAI API.

## Features

- **Real-time Conversation:** Engage in natural language conversations with the GPT-4o model.
- **Session Management:** Chat history is maintained across the session to provide a coherent conversation experience.
- **Easy Configuration:** API keys and other configuration data are loaded from a JSON file, making the setup process straightforward.
- **Streamlit Interface:** Utilizes Streamlit's components for an intuitive and user-friendly chat interface.

## Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.7 or higher
- Pip (Python package installer)
- An OpenAI API key (this is required to access the GPT-4o model)

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/Ashani-Sansala/GeniChat.git
    cd genichat
    ```

2. **Install the required Python packages:**

    ```bash
    pip install -r requirements.txt
    ```

3. **Create a `config.json` file:**

    In the src directory of the project, create a `config.json` file and add your OpenAI API key:

    ```json
    {
        "OPENAI_API_KEY": "your-openai-api-key-here"
    }
    ```

4. **Run the Streamlit app:**

    ```bash
    streamlit run src\main.py
    ```

## Usage

Once the Streamlit app is running, you can start interacting with GeniChat by entering your queries into the chat input box. The bot will respond in real-time using the GPT-4o model.

## Configuration

The OpenAI API key is managed through the config.json file. This keeps your key secure and allows for easy updates without modifying the main application code.

