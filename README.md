# NLP-varun-sain-2301201134-project-2

Project 2: Customer Support Chatbot for Online Shopping

Goal: Build a chatbot to handle basic customer queries (order tracking, return policies, delivery, product FAQs).

Concepts Used:

Intent recognition (classify query type)

Named Entity Recognition (extracting order numbers, product names)

Rule-based and similarity-matching responses

Tools: Python (NLTK, spaCy, Rasa for advanced bots)

Dataset: Sample customer queries mapped to responses (example:

"Where is my order 12345?" → "Your order 12345 is out for delivery."

"How can I return a product?" → "You can return products within 15 days via our online portal.")

Workflow Solution:

Preprocess user query: Tokenize, remove stopwords, lemmatize.

Intent Classification: Order status, return policy, product info, etc.

Entity Extraction: For order numbers, product names using NER.

Response Generation: Provide the right predefined response from dataset.
