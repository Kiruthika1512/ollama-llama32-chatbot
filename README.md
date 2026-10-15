# Local AI Chatbot Using Ollama, Llama 3.2, Python & Streamlit

## Project Overview

This project is a locally running AI chatbot developed using Python, Ollama, Meta's Llama 3.2 language model, and Streamlit.

The goal of this project was to understand how a Python application can interact with a large language model (LLM) and deliver responses through a simple, interactive user interface.

Instead of relying entirely on a hosted chatbot service, this application uses Ollama to run the language model locally.

## Key Features

* Interactive chatbot interface built with Streamlit.
* Integration with the Llama 3.2 model through Ollama.
* Python-based communication between the application and the language model.
* Local model execution without requiring a hosted LLM API for inference.
* A foundation for exploring conversational memory and more advanced AI application features.

*Note: Features listed above should reflect the functionality implemented in the actual application.*

## Technology Stack

* **Programming Language:** Python
* **Language Model Runtime:** Ollama
* **Large Language Model:** Llama 3.2
* **User Interface:** Streamlit
* **Development Environment:** Visual Studio Code

## How It Works

1. The user enters a message through the Streamlit interface.
2. The Python application sends the message to the locally running Llama 3.2 model through Ollama.
3. The language model generates a response.
4. The application displays the response in the chatbot interface.

This workflow demonstrates how Python, a locally running language model, and a user interface can work together in an AI application.

## Prerequisites

Before running the application, install:

* Python
* Ollama
* The Llama 3.2 model
* The Python dependencies listed in `requirements.txt`

## Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/ollama-llama32-chatbot.git
```

Replace `YOUR-USERNAME` with your GitHub username.

### 2. Navigate to the Project Folder

```bash
cd ollama-llama32-chatbot
```

### 3. Install the Python Dependencies

```bash
pip install -r requirements.txt
```

### 4. Install and Run Ollama

Install Ollama from its official website:

https://ollama.com/

Download the Llama 3.2 model:

```bash
ollama pull llama3.2
```

Ensure Ollama is running before launching the application.

### 5. Launch the Chatbot

If the main application file is named `app.py`, run:

```bash
streamlit run app.py
```

If your Python file has a different name, replace `app.py` with the correct filename.

## Project Structure

```text
ollama-llama32-chatbot/
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
└── screenshots/
```

The structure above is illustrative and should be updated to match the actual repository.

## Learning Outcomes

Through this project, I explored:

* Connecting Python applications to a locally running language model.
* Using Ollama to run and interact with Llama 3.2.
* Building an interactive interface using Streamlit.
* Understanding the basic request-and-response workflow of an LLM-powered application.
* Organizing an AI project for documentation and version control.

## Future Improvements

* Add conversational memory.
* Improve the chat interface and conversation history.
* Add error handling and input validation.
* Explore additional local language models.
* Develop more practical applications using large language models.

## Conclusion

This project represents an early step in my journey into local AI development and large language models.

Building it helped me connect Python programming, local model execution, and interface development in one working application.

I look forward to extending this foundation through further experimentation and practical AI projects.
