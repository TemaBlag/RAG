# RAG from Scratch & Text Splitting Techniques

This repository contains notebooks and code examples related to the course ["RAG from Scratch"](https://www.youtube.com/watch?v=sVcwVQRHIc8&t=3s) offered by [LangSmith](https://www.langchain.com/langsmith). The course provides a comprehensive introduction to Retrieval-Augmented Generation (RAG), covering essential concepts, strategies, and implementations and explore the 5 levels of text splitting from tutorial by [Greg Kamradt](https://www.youtube.com/watch?v=8OJC21T2SL4&t=3274s).
![RAG](https://github.com/user-attachments/assets/669bccea-3164-42e6-bf07-4e75ac16b942)


## Course Overview

### RAG from Scratch
The course covers key topics, including:

1. **Introduction to RAG**: Fundamentals, components, and significance in Natural Language Processing (NLP).
2. **Query Analysis**: Techniques for analyzing queries and determining appropriate retrieval strategies.
3. **Self-RAG and Adaptive RAG**: Advanced strategies incorporating self-reflection and adaptive retrieval techniques.
4. **Implementing RAG**: Hands-on implementation of RAG systems using various models and frameworks.
5. **Evaluation Metrics**: Understanding and applying metrics for evaluating RAG system performance.

### 5 Levels Of Text Splitting
This tutorial explores five levels of text splitting, an effective strategy for enhancing language model performance, particularly for long inputs:

1. **Character Splitting**: Basic static character chunks.
2. **Recursive Character Text Splitting**: Chunking using separators recursively.
3. **Document Specific Splitting**: Tailored methods for different document types (PDF, Python, Markdown).
4. **Semantic Splitting**: Chunking based on embedding walks.
5. **Agentic Splitting**: An experimental agent-like chunking method.

*Bonus Level:* **Alternative Representation Chunking + Indexing**: Derivative representations for improved retrieval.

## Notebooks

Each notebook contains detailed comments explaining the code and concepts, as well as modifications made to adapt the code for use with Hugging Face API keys instead of OpenAI API keys.
