SkyScout: Flight Query Assistant - SkyScout is an AI-powered flight query assistant that retrieves live flight information and schedule updates using the AeroDataBox API. It also uses a Retrieval-Augmented Generation (RAG) pipeline to answer user queries from a knowledge base, providing a conversational interface built with Streamlit.

Features - Live Flight Information: Fetches flight details and schedule updates using the AeroDataBox API.
RAG-Based Question Answering: Retrieves relevant information from a knowledge base to answer user queries. 
Semantic Search: Uses Sentence Transformers to generate text embeddings for retrieving relevant information.
Vector Database: Uses ChromaDB to store and search vector embeddings.
Interactive Chat Interface: Provides a conversational question-answering workflow through Streamlit.

Tech Stack -
Programming Language: Python
Flight Data API: AeroDataBox API
NLP & Embeddings: Sentence Transformers
Vector Database: ChromaDB
Frontend: Streamlit
Architecture: Retrieval-Augmented Generation (RAG)

How It Works -
Flight Data Retrieval: The application fetches flight information and schedule updates from the AeroDataBox API.
Knowledge Retrieval: User questions are processed to retrieve relevant information from the knowledge base.
Semantic Matching: Sentence Transformers generates embeddings to identify relevant text based on semantic similarity.
Vector Search: ChromaDB stores and retrieves relevant vector representations.
Response Generation: The retrieved context is used in the question-answering pipeline to formulate relevant responses.

User Interaction: Streamlit provides the interface through which users can ask questions and interact with the assistant.
