# Document Intelligence RAG - My Learning Implementation

## About This Repository

This repository contains my personal implementation and exploration of Retrieval-Augmented Generation (RAG) techniques. As a data analyst, I worked through these notebooks to understand how to build intelligent document query systems that can extract insights from large document collections.

**Credit**: This project builds upon the excellent [RAG From Scratch](https://github.com/langchain-ai/rag-from-scratch) educational materials by LangChain. I implemented these concepts myself to solidify my understanding.

## What is RAG?

RAG (Retrieval-Augmented Generation) is a technique that makes AI language models smarter by:
- Retrieving relevant information from external documents
- Using that information to generate more accurate responses
- Enabling AI to answer questions about data it wasn't trained on

Think of it like giving an AI assistant access to a library so it can look up facts before answering your questions - perfect for analyzing business documents, reports, and datasets!

## Why I Built This

As a data analyst with 2 years of experience working with business intelligence and reporting, I wanted to understand:
- How to build AI systems that can query large collections of reports and documentation
- Different retrieval strategies for extracting insights from unstructured data
- Advanced RAG patterns that can be applied to business analytics use cases
- How to leverage RAG for automated report analysis and data-driven decision making

This knowledge helps me bridge the gap between traditional data analysis and AI-powered document intelligence.

## What's Inside

This repository includes notebooks covering:

### Fundamentals (Notebooks 1-4)
- Document loading and text splitting
- Vector embeddings and similarity search
- Basic RAG pipeline: Index → Retrieve → Generate

### Query Techniques (Notebooks 5-9)  
- Query transformation and expansion
- Multi-query retrieval
- Query routing strategies

### Advanced Patterns (Notebooks 10-18)
- Query structuring for databases
- Multi-representation indexing
- Self-corrective RAG
- Adaptive routing

## Technologies Used

- **LangChain** - LLM application framework
- **OpenAI/Anthropic** - Language models
- **FAISS/Chroma** - Vector databases
- **Python** - Implementation language

## How to Run

### Prerequisites
- Python 3.8 or higher
- OpenAI API key (get one at https://platform.openai.com)

### Setup

1. **Clone this repository**:
```bash
   git clone https://github.com/Niveda-227/document-intelligence-rag.git
   cd document-intelligence-rag
```

2. **Install dependencies**:
```bash
   pip install langchain langchain-openai langchain-community faiss-cpu jupyter
```

3. **Set your API key**:
   
   **Mac/Linux:**
```bash
   export OPENAI_API_KEY='your-api-key-here'
```
   
   **Windows:**
```bash
   set OPENAI_API_KEY=your-api-key-here
```

4. **Start Jupyter**:
```bash
   jupyter notebook
```

5. **Open any notebook** and run the cells!

## My Key Learnings

**Most Important Takeaway**: The quality of your retrieval step directly impacts the quality of generated answers. Good chunking and embedding strategies are crucial for accurate document analysis.

**Biggest Challenge**: Balancing chunk size - too small loses context, too large loses precision. This is especially important when working with business reports that have complex structures.

**Most Useful Technique**: Multi-query retrieval significantly improved results by rephrasing questions from different angles, making it easier to extract insights from diverse document types.

## What I Plan to Build Next

- [ ] RAG system for analyzing business reports and quarterly earnings calls
- [ ] Automated insight extraction from market research documents
- [ ] Document comparison tool for competitive analysis
- [ ] RAG-powered data dictionary and documentation assistant
- [ ] Dashboard query assistant that answers questions about KPIs and metrics

## Potential Applications in Data Analytics

- **Report Summarization**: Automatically generate summaries from lengthy business reports
- **Data Documentation**: Query internal documentation and data dictionaries
- **Competitive Intelligence**: Analyze competitor reports and market research
- **Automated Insights**: Extract key findings from multiple data sources
- **Knowledge Management**: Build searchable knowledge bases from company documents

## Resources & References

- Original Notebooks: [LangChain RAG From Scratch](https://github.com/langchain-ai/rag-from-scratch)
- Video Series: [RAG From Scratch Playlist](https://youtube.com/playlist?list=PLfaIDFEXuae2LXbO1_PKyVJiQ23ZztA0x)
- LangChain Docs: [python.langchain.com](https://python.langchain.com)

## License

This is an educational project. Original materials are from LangChain under MIT license.

## Contact

Questions or want to discuss RAG implementations for data analytics?

- GitHub: [Niveda-227](https://github.com/Niveda-227)
- LinkedIn: [Niveda Jawahar](https://www.linkedin.com/in/nivedajawahar/)

---

*Learning in public. Building AI skills to enhance data analytics capabilities.*