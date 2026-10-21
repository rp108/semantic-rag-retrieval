My hands on exploration of semantic search, evaluation of retrieved info, and retrieval-augmented generation. Idea is to gain first hand experience of engineering trade offs involved in semantic search systems

Project objectives -
a. Start with keyword based retrieval to establish baseline
b. Impelement semantic retrieval using text embeddings
c. Compare both retrieval approaches using metrics, namely Recall@k and Mean Reciprocal Rank (MRR)
d. Expose REST interface to the retrieval service
e. Add RAG pipeline that generates responses grounded in retrieved docs
f. Test retrieval quality, correctness, failures

Architecture -

a. Doc corpus - A labeled corpus of docs
b. Retrieval - Keyword and semantic (embeddings based)
c. Evaluation - Reproducible queries and relevance judgments
d. API - A service for submitting search queries and retrieving relevant docs
e. RAG - An add on to generate answers grounded in retrieved docs

Tech stack - 

a. Python
b. FastAPI
c. Text embeddings
d. Pytest

Status -

Repo setup done. Moving on to retrieval and eval implementation