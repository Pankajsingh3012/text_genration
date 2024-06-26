# text_genration

In this notebook we're going to augment the knowledge base of our LLM with additional data:

We will walk through how to load data, local text file using a DocumentLoader, split it into chunks, and store it in a vector database using ChromaDB.
And using Question Answering on Own Data
Inretrieval augmented generation (RAG) framework, an LLM retrieves contextual documents from an external dataset as part of its execution. This is useful when we want to ask questions about specific documents (e.g., PDFs, videos, etc).
