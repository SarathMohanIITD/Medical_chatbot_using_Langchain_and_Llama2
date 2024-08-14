# Retrieval-Augmented Medical Conversational Bot

This repository contains the code for a Retrieval-Augmented Medical Conversational Bot. The bot leverages retrieval-augmented generation (RAG) techniques to provide accurate and contextually relevant responses to medical queries.


## Introduction

The Retrieval-Augmented Medical Conversational Bot is designed to assist users by providing medical information and answering health-related questions. It combines the power of large language models with a retrieval mechanism to enhance the accuracy and relevance of the responses.
The medical information is fed through a pdf document in Data/ folder
## Features

- **Accurate Responses**: Utilizes retrieval-augmented generation to provide precise answers.
- **Context-Aware**: Understands and maintains context throughout the conversation.
- **Customizable**: Easily adaptable to different medical domains and datasets.

## Architecture

The bot's architecture includes the following components:

1. **Language Model (LLM)**: Utilizes a pre-trained language model for generating responses. 
2. **Retrieval Mechanism**: Employs a retrieval system using Langchain
3. **Embedding Database**: Stores embeddings of medical documents for efficient retrieval using Pinecone .

## Download the model
```bash
## Download the Llama 2 Model:

llama-2-7b-chat.ggmlv3.q4_0.bin


## From the following link:
https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main

```

## Installation

To install and set up the project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/SarathMohanIITD/Retrieval-Augmented-Medical-Conversational-Bot.git
    cd Retrieval-Augmented-Medical-Conversational-Bot
    ```

2. Create and activate a virtual environment:
    ```bash
    python3 -m venv venv
    source venv/bin/activate  
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To start the bot, run the following command:
```bash
# run the following command
python store_index.py
```
```bash
# Finally run the following command
python app.py
```
