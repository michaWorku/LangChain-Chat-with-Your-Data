# LangChain: Chat With Your Data  

## Course Overview  
[LangChain: Chat With Your Data](https://www.deeplearning.ai/short-courses/langchain-chat-with-your-data/) teaches you how to build AI-powered chatbots that interact with your own data using **Retrieval Augmented Generation (RAG)**. Led by LangChain creator **Harrison Chase**, this course covers:  

- **Document loading** – Access data from various sources using over 80 unique loaders.  
- **Document splitting** – Optimize data retrieval with effective chunking techniques.  
- **Vector stores & embeddings** – Store and retrieve data efficiently.  
- **Advanced retrieval techniques** – Improve search results using metadata, MMR, and LLM-aided retrieval.  
- **Building chatbots** – Create interactive bots that answer questions based on private data.  

By the end of this course, you’ll be able to **build practical LLM-powered applications** that dynamically retrieve and respond to queries. 🚀  

## Course Contents  

### 1. Introduction  
- **Retrieval Augmented Generation (RAG):** LLMs retrieve relevant documents from external datasets to generate responses.  
- **Use Cases:** Query documents like PDFs, websites, and databases.  

### 2. [Document Loading](https://github.com/michaWorku/LangChain-Chat-with-Your-Data/blob/main/01_document_loading.ipynb)  
- **Loaders** – Tools for accessing and converting data into structured document objects.  
- **Supported Sources:** PDFs, HTML, JSON, Word, PowerPoint, YouTube, arXiv, Notion, databases, etc.  

### 3. [Document Splitting](https://github.com/michaWorku/LangChain-Chat-with-Your-Data/blob/main/02_document_splitting.ipynb) 
- **Chunking** – Splitting large documents while maintaining context.  
- **Splitting Methods:** Character, token, and **context-aware** (using document structure).  

### 4. [Vector Stores & Embeddings](https://github.com/michaWorku/LangChain-Chat-with-Your-Data/blob/main/03_vectorstores_and_embeddings.ipynb) 
- **Embeddings:** Capture document meaning as numerical vectors.  
- **Vector Stores:** Store and retrieve embeddings for semantic search.  
- **Workflow:** Load → Split → Embed → Store → Retrieve.  

### 5. [Retrieval](https://github.com/michaWorku/LangChain-Chat-with-Your-Data/blob/main/04_retrieval.ipynb) 
- **Semantic similarity search** – Find relevant documents using vector representations.  
- **Advanced Techniques:**  
  - **Maximum Marginal Relevance (MMR):** Ensure diversity in retrieved results.  
  - **LLM-aided retrieval:** Enhance query understanding using AI.  
  - **Compression:** Fit more context by summarizing retrieved documents.  

### 6. [Question Answering](https://github.com/michaWorku/LangChain-Chat-with-Your-Data/blob/main/05_question_answering.ipynb)  
- **RetrievalQA Chain:**  
  - Query the vector store.  
  - Retrieve relevant documents.  
  - Pass the documents to an LLM for response generation.  
- **Methods:** Basic retrieval, map_reduce, refine, and **LangSmith** for evaluation.  

### 7. [Chatbot Development](https://github.com/michaWorku/LangChain-Chat-with-Your-Data/blob/main/06_chat.ipynb)  
- **Conversational Retrieval Chain:** Combine retrieval with memory for multi-turn interactions.  
- **Build Your Own Chatbot:**  
  - Load and split documents.  
  - Create embeddings and store them in a vector database.  
  - Implement a retriever and chat chain.  
  - Manage conversation history.  

## Notebooks  
1. [Document Loading](https://github.com/michaWorku/LangChain-Chat-with-Your-Data/blob/main/01_document_loading.ipynb)  
2. [Document Splitting](https://github.com/michaWorku/LangChain-Chat-with-Your-Data/blob/main/02_document_splitting.ipynb)  
3. [Vector Store & Embeddings](https://github.com/michaWorku/LangChain-Chat-with-Your-Data/blob/main/03_vectorstores_and_embeddings.ipynb)  
4. [Retrieval](https://github.com/michaWorku/LangChain-Chat-with-Your-Data/blob/main/04_retrieval.ipynb)  
5. [Question Answering](https://github.com/michaWorku/LangChain-Chat-with-Your-Data/blob/main/05_question_answering.ipynb)  
6. [Chatbot](https://github.com/michaWorku/LangChain-Chat-with-Your-Data/blob/main/06_chat.ipynb)  

## Getting Started  
1. Install required dependencies.  
2. Load and preprocess your dataset.  
3. Run the notebooks in order to build a **data-aware chatbot**.  

## References  
- [Course Link](https://www.deeplearning.ai/short-courses/langchain-chat-with-your-data/)  

This course equips you with the skills to create **AI-powered chatbots** that can search, retrieve, and generate answers from your private data. 🚀
