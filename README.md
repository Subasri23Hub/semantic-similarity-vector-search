# Semantic Similarity & Vector Search System (FAISS + API Embeddings)

##  Overview
This project demonstrates a practical implementation of semantic similarity search using embeddings and vector database concepts. It combines FAISS-based vector indexing with API-generated embeddings to enable efficient similarity retrieval.

Additionally, the project includes a lightweight web interface to interact with the system, simulating real-world GenAI search workflows.

---

##  Objectives
- Understand how embeddings represent semantic meaning
- Implement similarity search using cosine similarity
- Explore vector database concepts using FAISS
- Build an end-to-end pipeline from data → embeddings → retrieval → interface

---

##  Key Concepts Covered
- Embeddings
- Semantic Similarity
- Cosine Similarity
- Vector Databases
- Nearest Neighbor Search (NNS)
- Approximate Nearest Neighbor (ANN)
- FAISS Indexing

---

##  Tech Stack
- Python
- FAISS (Facebook AI Similarity Search)
- Embedding API (Grok / external embedding service)
- Flask (for backend API)
- HTML/CSS (basic frontend)
- Pyngrok (for exposing local server)

---

##  Project Workflow

1. **Data Preparation**
   - Input text/sentences processed for embedding generation

2. **Embedding Generation**
   - Text converted into vector representations using an API-based embedding model

3. **Vector Indexing**
   - Embeddings stored and indexed using FAISS for efficient retrieval

4. **Similarity Search**
   - Query is converted into embedding
   - Cosine similarity used to find closest matches

5. **Application Layer**
   - Flask backend serves results
   - Simple UI allows interaction with the system

---

##  Output & Demonstration
The project includes:
- Similarity score outputs
- Retrieval results based on semantic meaning
- Screenshots included in the repository

---

##  Project Structure

├── semantic_similarity_vector_search.ipynb

├── vector_search_project_overview.pptx

├── output_screenshots

├── README.md


---

##  How to Run

### 1. Install Dependencies

pip install sentence-transformers faiss-cpu flask flask-cors pyngrok


### 2. Run Notebook / Script
- Execute the notebook step-by-step in Google Colab or locally

### 3. Launch Application
- Flask server will start
- Ngrok tunnel exposes the app publicly

---

##  Key Learnings
- How embeddings capture semantic meaning beyond keywords
- How FAISS enables fast vector-based search at scale
- Difference between traditional search vs semantic search
- Practical understanding of vector database workflows

---

##  Future Improvements
- Integrate cloud vector databases (Pinecone / Weaviate / Milvus)
- Optimize search using Approximate Nearest Neighbor techniques
- Deploy as a scalable API service
- Enhance frontend for better visualization

---

##  Conclusion
This project demonstrates a foundational implementation of semantic search systems used in modern GenAI applications. It bridges theoretical understanding with practical implementation, covering both backend vector search and basic application integration.

---

##  Author
Subasri B | Gen AI Intern @Sourcesys Technologies
