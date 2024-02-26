## Amazon Product Autocomplete

This notebook provides a solution for providing product recommendations based on the search query from a user. The notebook implements two approachs:

- Keyword based search using TheFuzz
- Semantic search using sentence-transformers and Faiss

The steps implemented in this notebook are:

- Data loading and basic analysis
- Data cleaning
- Data preprocessing
- Search implementation
- Testing

For testing, we have considered three strings,

- "Fire TV" straightforward keyword based search
- "A birthday gift for kids party" for semantic based search
- "Dire tablet" for misspelling text search

Further improvements needed:

- Optimize search
- Semantic search needs improvement. Currently, it is done only on product names (extracted from the data); ideally it should be done on all names
- More comprehensive testing
