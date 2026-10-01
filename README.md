# 🤖 My AI Q&A Bot using Ollama

A simple command-line **AI Question & Answer chatbot** built with Python and **Ollama**.
The bot uses the **Llama 3.2** language model to answer user questions and maintains conversation history during the session.

## 📌 Features

* 💬 Interactive question-and-answer chatbot
* 🧠 Uses the Llama 3.2 AI model
* 🔄 Maintains conversation history
* 🖥️ Runs directly in the terminal
* 🚪 Type `exit` to stop the chatbot
* 🐍 Built using Python

## 🛠️ Technologies Used

* **Python**
* **Ollama**
* **Llama 3.2**

## 📋 Requirements

Before running the project, make sure you have:

1. Python 3.8 or later
2. Ollama installed
3. Llama 3.2 model downloaded
4. Ollama Python package installed

## ⚙️ Installation

### 1. Install Python

Download and install Python from the official Python website.

### 2. Install Ollama

Install Ollama on your computer and make sure the Ollama service is running.

### 3. Download Llama 3.2

Open your terminal and run:

```bash
ollama pull llama3.2
```

### 4. Install the Python Ollama package

Run:

```bash
pip install ollama
```

## 📂 Project Structure

```text
AI-QA-Bot/
│
├── chatbot.py
└── README.md
```

## ▶️ How to Run

Save the Python code in a file named:

```text
chatbot.py
```

Then run:

```bash
python chatbot.py
```

You should see:

```text
My AI Q&A Bot
Type 'exit' to stop.

You:
```

Enter your question:

```text
You: What is artificial intelligence?
```

The bot will generate an answer using Llama 3.2:

```text
Bot: Artificial Intelligence is the simulation of human intelligence
by computer systems...
```

To stop the program, type:

```text
exit
```

The output will be:

```text
Bot: Goodbye!
```

## 🧩 How the Code Works

### Import Ollama

```python
import ollama
```

This imports the Ollama Python library so that Python can communicate with the local AI model.

### Store Conversation History

```python
messages = []
```

The `messages` list stores previous user questions and bot responses. This allows the chatbot to maintain context throughout the conversation.

### Get User Input

```python
ques
```
