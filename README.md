# Sydney-Beach-Query-Model
Custom Large Language Model (LLM) that answers questions about Sydney beaches using Cohere API for embeddings and AnnoyIndex for efficient search. Input natural language queries, and the model retrieves relevant text to provide accurate responses. Built using Python, NLP, and machine learning techniques.



---

# **LLM from Scratch: Sydney Beach Query Model**

This repository contains my journey in building a Large Language Model (LLM) from scratch using the Cohere API for embeddings and AnnoyIndex for efficient search. The project focuses on answering natural language questions based on a text archive about Sydney beaches.

---

## **Overview**

This project demonstrates how to build a custom LLM capable of:
- Extracting relevant information from a given text archive.
- Responding to user questions based on pre-trained embeddings.
- Using AnnoyIndex for efficient search and retrieval of relevant text sections.

---

## **Key Features**

- **Cohere API**: Generates high-quality embeddings for text and answers user queries.
- **AnnoyIndex**: Efficient search and retrieval of closest matching text segments.
- **Natural Language Processing**: Understands and responds to user queries with relevant context.

---

## **Setup Instructions**

### 1. Clone the repository:
```bash
git clone https://github.com/yourusername/llm-sydney-beach-query.git
cd llm-sydney-beach-query
```

### 2. Install dependencies:
```bash
pip install cohere annoy numpy pandas
```

### 3. Get your Cohere API Key:
Sign up for [Cohere](https://cohere.com) and generate an API key.

### 4. Set up your API Key:
Replace `<Get your Cohere API Key from cohere.com>` in the code with your own API key.

### 5. Run the script:
```bash
python llm_query.py
```

---

## **Project Workflow**

1. **Input Processing**: The model processes a predefined text about Sydney beaches, splitting it into paragraphs and cleaning up unnecessary spaces.
   
2. **Embeddings Creation**: Using Cohere’s API, embeddings are generated for the text segments.

3. **Search Indexing**: AnnoyIndex is used to store and search through the embeddings.

4. **Question Answering**: The user provides a query, and the model retrieves relevant context and generates a response using the Cohere model.

---

## **Example Queries**

```python
# Sample question
question = "Which Sydney beach has a rock pool?"

# LLM Response
Bronte Beach: It’s a smaller, quieter beach with a beautiful park area and a natural rock pool that's ideal for swimming.
```

### **Other Example Queries**
- "Which Sydney beach is for family?"
- "Which Sydney beach should I visit?"

---
