# Ollama Basic Chatbot

A simple Q&A chatbot built with Streamlit, LangChain, and the Ollama model. This project demonstrates how to create an interactive chatbot interface that leverages LangChain's prompt templates and output parsers along with the Ollama language model.

## Overview

This project implements a basic Q&A chatbot that:

* Uses **Streamlit** for a simple web interface.
* Leverages **LangChain** for prompt templating and chaining.
* Integrates with the **Ollama** model to generate responses.
* Demonstrates Langsmith tracking by configuring environment variables.

## Features

* **Interactive UI:** Powered by Streamlit to quickly prototype and test chat interactions.
* **Customizable Prompt:** Uses LangChain’s `ChatPromptTemplate` to define system and user messages.
* **Model Selection:** Easily select an open source model (e.g., "mistral") from the sidebar.
* **Adjustable Parameters:** Control the generation settings like temperature and max tokens via sidebar sliders.
* **Environment Tracking:** Integrates with Langsmith for tracking chatbot interactions.
