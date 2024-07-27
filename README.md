# rag

```mermaidgraph LR; participant User as "User" participant RAG as "Retrieval-Augmented Generation" participant Knowledge Base as "Knowledge Base" participant Generator as "Generator" participant Ranker as "Ranker" participant Contextualizer as "Contextualizer" User->>RAG: Input (prompt or query) RAG->>Knowledge Base: Retrieve relevant documents Knowledge Base->>RAG: Retrieved documents RAG->>Contextualizer: Contextualize input and documents Contextualizer->>Generator: Contextualized input and documents Generator->>RAG: Generated text RAG->>Ranker: Rank generated text Ranker->>RAG: Ranked generated text RAG->>User: Output (generated text)```
