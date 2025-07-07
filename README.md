# Voice-Based-NLP-Chatbot

This project is a voice-based chatbot that can understand your speech, reply with natural-sounding answers, and even talk back to you! It has two main parts:

 1. Model Fine-Tuning (Notebook 1)
A custom dataset with human-like conversations (query and response pairs) is used.

The dataset is cleaned and processed.

We fine-tune the DialoGPT-small model using Hugging Face's transformers library.

The trained model is saved and used in the second part of the project.

2. Voice Interaction (Notebook 2)
You upload a voice recording (or any audio file).

The program converts your voice to text using SpeechRecognition.

That text is passed to the chatbot model to get a reply.

The reply is turned into speech using gTTS, and you can listen to it.

Tools & Libraries
Python

Google Colab

Hugging Face (transformers, datasets)

PyTorch

SpeechRecognition

gTTS (Google Text-to-Speech)

pydub
