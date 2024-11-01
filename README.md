# *Talking to the sources. On the application of Retrieval-Augmented-Generation in historical research.*

This repository contains code and data from my Master's thesis project, which explores the application of a Retrieval-Augmented Generation (RAG) system to support historical research. The project focuses on the historical analysis of documents, particularly in assessing how a RAG model can be tailored for historiographical tasks such as contextual retrieval, critical analysis, and interpretive support.

## Project Overview

The use of RAG models in historical studies offers promising potential, enabling researchers to navigate and analyze vast corpora of historical texts. My study specifically examines historical sources concerning "Women in National Socialism" using the *NS Frauen-Warte* periodical as a case study. The RAG system is used to support historians in locating relevant content, critically engaging with it, and deriving interpretive insights.

### Key RAG system Components
- **Retriever:** A vector-based search mechanism that identifies relevant source segments from an indexed corpus.
- **Generator:** A language model tasked with producing contextually-informed responses based on retrieved historical data, offering citations back to the source material for transparency.

### Major Findings
The RAG system demonstrates utility in several areas:
1. **Enhanced Retrieval and Contextualisation**: The RAG model can effectively surface and contextualise relevant historical data, acting as a dynamic search tool that aligns closely with traditional historiographical methods.
2. **Interpretive Consistency**: The model reproduces content faithfully and provides coherent interpretations that align with the source material’s intent. It respects the *Vetorecht* of historical sources, ensuring generated responses do not contradict the original texts.
3. **Challenges and Limitations**: Data quality and OCR accuracy significantly impact performance, and prompt formulation is critical to system reliability. Additionally, for sensitive historical topics, the model requires cautious handling to avoid inadvertent bias amplification. Future improvements are suggested in prompt engineering and fine-tuning for historical context alignment.

## Repository Contents
- **Code Notebooks**: Jupyter notebooks demonstrating the setup, retrieval, and generation functions.
- **Sample Data**: Selected data excerpts and processing scripts from the *NS Frauen-Warte* dataset.
- **Evaluation Results**: Quantitative alignment, refutability, and safety assessments, along with qualitative analyses discussing the model's response coherence and historical relevance.

### Acknowledgments
Big thanks to my advisors and fellow students for all the support and feedback. Your insights really made a difference—thanks so much! 🌟
