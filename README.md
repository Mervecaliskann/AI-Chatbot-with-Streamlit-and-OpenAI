# AI-Chatbot-with-Streamlit-and-OpenAI

A interactive chatbot application built using Streamlit and OpenAI's GPT-4 model, providing a user-friendly interface for AI conversations.

## Features
- Real-time chat interface
  
- Persistent conversation history
  
- Integration with OpenAI's GPT-4 model
  
- Clean and intuitive UI with Streamlit
  
- System message initialization

## Code Structure

### Libraries Used
```python
from openai import OpenAI
import os
from dotenv import load_dotenv
import streamlit as st
```

## Key Components

Environment Setup

Loads API key securely from .env file

Initializes OpenAI client

## Session State Management

Maintains conversation history

Initializes system message

## Response Generation

Handles API calls to OpenAI

Processes user inputs

Manages message history

## UI Components

Header with "İlk Sohbet Botum"

Chat interface

Message input field

Message display area
