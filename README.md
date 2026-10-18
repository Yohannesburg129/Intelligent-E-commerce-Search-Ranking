# Intelligent E-commerce Search & Ranking

An end-to-end product search project using traditional information retrieval, semantic embeddings, and hybrid search.

## Project Objective

Build and compare different product retrieval algorithms to understand how keyword matching and semantic similarity can support e-commerce product discovery.

## Dataset

- Source: Amazon Products 2023 (Hugging Face)
- Products analyzed: 10,000
- Features: Product titles, descriptions, categories, and customer ratings

## Technologies

Python, Pandas, NumPy, Scikit-learn, Rank-BM25, Sentence Transformers, FAISS, Matplotlib, Seaborn, Jupyter Notebook.

## Search Algorithms

1. **TF-IDF:** Keyword-based retrieval using cosine similarity.
2. **BM25:** Probabilistic keyword ranking.
3. **Semantic Search:** Sentence Transformer embeddings with FAISS similarity search.
4. **Hybrid Search:** Combines BM25 and semantic rankings using Reciprocal Rank Fusion.

## Project Workflow

1. Data loading and exploratory analysis
2. Product text cleaning and preprocessing
3. TF-IDF retrieval implementation
4. BM25 retrieval implementation
5. Semantic embeddings and FAISS indexing
6. Search result comparison
7. Relevance evaluation using Precision@5 and NDCG@5
8. Hybrid search implementation
9. Final findings and business implications

## Key Learnings

- Different retrieval algorithms can prioritize different products for the same query.
- Keyword-based search emphasizes matching product terminology.
- Semantic search can identify products based on broader customer intent.
- Reciprocal Rank Fusion provides a straightforward method for combining multiple retrieval rankings.
- Offline relevance evaluation is important before making claims about search quality.

## Limitations

The evaluation uses a limited query set and provisional relevance judgments. Hybrid search was implemented but not formally evaluated against the other algorithms.

## Future Improvements

- Evaluate a larger and more diverse query set.
- Incorporate pricing, product availability, and customer ratings.
- Benchmark retrieval latency.
- Test whether ranking improvements affect customer engagement and conversion.

## Outcome

Built a functional product search pipeline demonstrating keyword retrieval, semantic embeddings, FAISS indexing, relevance evaluation, and hybrid ranking.
