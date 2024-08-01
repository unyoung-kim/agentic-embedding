# Agentic Embedding

Retrieval-Augmented Generation (RAG) systems are gaining significant popularity among legacy industries such as law, life sciences, and finance, where there are massive amounts of unstructured text that are multimodal. Gathering insights from these extensive piles of documentation previously involved manual searches and insight generation from graphs and diagrams, which are extremely time-consuming and laborious, even for highly intelligent individuals. Companies like Harvey and Hebbia that have recently bagged huge funds exemplify how RAG systems can expedite this process by not only finding relevant documents but also providing a GPT-like interface that directly answers user questions.

However, RAG systems often hallucinate, especially when they fail to find relevant answers from the pool of embedded documents. Achieving performance from 80% to 100% is extremely challenging but crucial especially for vertical use cases where mistakes can be costly and unforgiving.

While foundational models are often blamed and guardrails built with hallucination models (e.g., [Lynx](https://www.patronus.ai/blog/lynx-state-of-the-art-open-source-hallucination-detection-model)) are gaining popularity, the importance of embedding strategies and the limitations of multimodal embedding are less frequently discussed.

**Agentic Embedding** is a new AI engineering term that I coined, which implies a method of utilizing different prompts or methods to embed various types of modalities (e.g., text, tables, graphs, diagrams, photos, etc.). While the code serves as a simple demonstration of the concept, it also explores the current limitations of traditional OCR methods in processing unstructured multimodal documents.
