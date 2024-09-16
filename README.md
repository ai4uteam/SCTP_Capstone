# SCTP_Capstone
LLM with RAG

Capstone Project: Text Generation with Hugging Face and Chroma

A Powerful Question-Answering System using LangChain, Gradio, and Sentence Transformers

Overview: 
This project is a question-answering (QA) system built to process large text documents (AWS case studies and blogs) and provide relevant, helpful answers to user queries. By leveraging cutting-
edge NLP models like TinyLlama, Sentence Transformers for embedding, and Chroma for vector-based retrieval, the system efficiently retrieves and generates text responses based on user prompts.

This project uses Gradio to create an intuitive user interface, making it easy to interact with the model in real time.

Features: 
Document Processing: Automatically loads and splits large text files into manageable chunks.
Embeddings and Retrieval: Uses Sentence Transformers for embedding generation and Chroma as a vector store for efficient document retrieval.
Text Generation: Utilizes the TinyLlama model for high-quality text generation and answering user queries.
Interactive UI: Gradio-powered interface for simple, real-time interactions.
Customizable: The code is highly modular, allowing for easy customization and extension (e.g., using different models, datasets, or embeddings).

Tech Stack
Language Models: Hugging Face Transformers, TinyLlama, Sentence Transformers
Vector Store: Chroma
Frontend: Gradio
Libraries: LangChain, PyTorch, Matplotlib, Pandas, TQDM

Challenges and Learnings: 
This project posed several challenges, including managing memory consumption when loading large models and datasets, optimizing the chunking process for document retrieval, and fine-tuning model parameters for better response quality.

Through this, I learned the intricacies of Retrieval-Augmented Generation (RAG) and the importance of using efficient embeddings for large-scale document retrieval.
