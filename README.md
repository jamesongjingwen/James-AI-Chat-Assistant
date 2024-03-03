# James-AI-Chat-Assistant
An innovative Generative AI Chatbot project, incorporating Flask, OpenAI's embeddings, and RAG for enriched, intuitive, and dynamic conversational experiences.

<img src="https://raw.githubusercontent.com/jamesongjingwen/James-AI/Chat-Assistant/master/Chatbot Image.png" width="500" height="auto">

Project Overview

Title: James' AI Chat Assistant

Objective: The goal of this project is to create a Generative AI chatbot that utilises natural language processing and machine learning to deliver rich, intuitive, and dynamic conversational experiences to users.
Key Features

    Real-time Conversational Capabilities: The chatbot is designed to handle real-time interactions, providing immediate and contextually relevant responses to user queries.
    Document-based Learning: Utilising an unstructured dataset (Summary.doc) about James' background, the chatbot can extract information to enrich conversations with background knowledge.
    Adaptive Response Generation: Incorporating RAG (Retrieval-Augmented Generation) to enhance response quality by retrieving relevant information from a dataset and generating comprehensive answers.
    User-friendly Interface: A web interface (chat.html) built with Flask, offering users an easy and accessible way to interact with the chatbot.

Technologies Used

    Flask: Chosen for its simplicity and efficiency in setting up a lightweight web server for the chatbot interface.
    OpenAI Embeddings and RAG: These technologies are at the forefront of AI research, offering state-of-the-art capabilities for understanding and generating human-like text.
    FAISS: Utilised for efficient similarity search and clustering of large datasets, enabling the chatbot to quickly retrieve relevant information.
    langchain_community and langchain_openai Libraries: These libraries are integrated to leverage advanced NLP models and streamline the development of conversational AI applications.

Design Choices

    Flask as the Web Framework: Flask was selected for its ease of use and ability to rapidly prototype web applications, making it ideal for this project's scope and the need for a simple yet effective user interface.
    Integration of RAG and OpenAI Embeddings: These choices were motivated by the desire to push the boundaries of what is possible with conversational AI, ensuring the chatbot not only responds accurately but also incorporates a depth of knowledge and understanding in its responses.
    FAISS for Document Retrieval: The inclusion of FAISS was a strategic decision to enhance the chatbot's ability to access and utilise the unstructured dataset, ensuring responses are informed and contextually grounded.
    Custom Text Splitter: The development of a SimpleCharacterTextSplitter was a tailored solution to overcome challenges related to handling large documents, ensuring efficient processing and utilisation of the dataset. Chunk Size chosen was 500 characters because each section on the unstructured dataset is 350 characters. Chunk overlap chosen was 100 characters to ensure that context can be brought forward to the next chunk. 

Conclusion

This project demostrates the potential of integrating advanced technologies like RAG and OpenAI embeddings into chatbot development. The design choices were driven by the ambition to create a chatbot that not only understands and responds to user queries in real-time but also incorporates a depth of knowledge and adaptability in its interactions. Through this innovative approach, the project aims to offer users a unique and enriched conversational experience.
