# GenAI-chatbot-RAG
In this project, I build Gen AI chatbot using RAG, langchain, open source LLLM-Mistral 7B instruct and streamlit
You need to download mistral 7B instruct gguf from huggingface

Generative AI-based Chatbot for Field Insights
Welcome to the Generative AI-based Chatbot project! This application leverages advanced AI technologies to provide insights from field issues, making it a helpful companion for troubleshooting and understanding problems in the field.

Features
Document Handling: Automatically loads and processes PDF documents from a specified directory to extract relevant information.
Text Processing: Utilizes a recursive character text splitter to manage large text data by breaking it into manageable chunks.
Embeddings and Vector Store: Implements deep learning models to create embeddings for text chunks, storing them in a FAISS vector store to facilitate efficient retrieval.
Conversational AI: Integrates a conversational retrieval chain using a language model to provide meaningful responses to user queries.
Memory Management: Maintains conversation history to provide context-aware interactions.
Streamlit Interface: Offers a user-friendly web interface built with Streamlit, featuring a chat interface for easy communication.
Technology Stack
Streamlit: Provides the framework for building the interactive web application.
Langchain: Enables document loading, text processing, and chain creation for conversational AI.
HuggingFace Embeddings: Utilizes pre-trained models for generating text embeddings.
FAISS: Facilitates fast and efficient similarity search for vectorized text data.
Ctransformers: Powers the language model used for generating responses.
Installation
Clone the repository:

bash
git clone https://github.com/yourusername/field-insights-chatbot.git
Navigate to the project directory:

bash
cd field-insights-chatbot
Install the required packages:

bash
pip install -r requirements.txt
Run the Streamlit app:

bash
streamlit run app.py
Usage
Upload your PDF documents to the data/ directory.
Start the Streamlit app and interact with the chatbot by asking questions related to field issues.
The chatbot will provide insights based on the documents processed and the conversational history.
Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue to discuss improvements or report problems.

License
This project is open-source and available under the MIT License.
