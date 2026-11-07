# Generative-AI-Chatbot
📌 Project Overview

Developed an interactive AI-powered chatbot using LangChain, Groq API, and Streamlit. The chatbot enables users to have natural, context-aware conversations with an AI assistant. By implementing session state management and conversation history, it retains previous interactions and uses them as context to generate relevant responses and maintain conversational continuity.

🚀 Features

AI-Powered Conversations: Generates intelligent responses using Groq API.

LangChain Integration: Manages LLM interactions and conversational workflows.

Streamlit Interface: Provides an interactive and user-friendly chat interface.

Session State Management: Maintains conversation data during an active session.

Conversation History: Stores previous user messages and AI responses.

Context-Aware Responses: Remembers previous conversation context to answer follow-up questions more effectively.

🛠️ Technologies Used

Python

LangChain

Groq API

Streamlit

Large Language Models (LLMs)

Session State Management

⚙️ How It Works

Users interact with the chatbot through the Streamlit interface.

User messages are processed using LangChain.

Previous conversation history is retrieved from Streamlit session state.

The conversation context is passed to the LLM through the Groq API.

The LLM generates a response based on the current query and previous conversation.

Both user messages and AI responses are stored in session state for subsequent interactions.

💡 Key Learning Outcomes

Integrating Large Language Models using LangChain.

Connecting external LLM services through Groq API.

Building interactive applications using Streamlit.

Implementing session-based conversation history.

Developing context-aware conversational AI applications.

🔮 Future Enhancements

Implement persistent conversation storage using a database.

Support multiple chat sessions.

Integrate Retrieval-Augmented Generation (RAG).

Add voice-based interaction.
