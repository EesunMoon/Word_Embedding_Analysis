# Word_Embedding_Analysis
## Overview
This project is part of the research conducted at the Complex Resilient Intelligent Systems Laboratory (CRIS Lab), focusing on Word Embedding & Analysis. The study explores sentence embeddings, ranking methodologies, and context vector analysis to gain deeper insights into word representations.

## Workflow
1.	**Data Collection**
-	Collect and preprocess textual data for embedding analysis.
2.	**Sentence Embedding & Ranking**
- Generate sentence embeddings using Sentence Transformer (Sentence Bert, Small LM)
- Based on Zipf’s Law, analyze word frequency distribution, group the sentences based on cosine similarity, and then apply ranking techniques.
- Implement ranking techniques to evaluate sentence similarity and relevance.
- Perform Linear Regression Analysis for statistical modeling and interpretation of embeddings.
3.	**Context Vector Analysis** (In progress)
-	Analyze contextual relationships between words.
-	Investigate how context influences word embeddings in different scenarios.

## Project Structure
- `dataset/` - Contains raw and processed data for embedding analysis.
- `sentence_embedding_ranking/` - Implements sentence embedding generation, Zipf’s Law analysis, ranking models, and linear regression analysis.
- `context_vector_analysis/` - (To be added) Analysis of contextual word vectors.
- `README.md` - Project documentation.

## Technologies Used
- Word Embeddings: BERT and Transformer-based models.
- Grouping: Greedy, Graph-based grouping, DBSCAN clustering
- Zipf’s Law: Analyzing word frequency distribution in the dataset.
- Ranking Methods: Cosine similarity
- Linear Regression: Statistical modeling of word embeddings.
- Context Analysis: (Planned) Contextual embedding techniques (ex. BERT)
