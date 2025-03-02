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
3.	**Context Vector Analysis**
- Analyze context vectors within transformer-based models, focusing on their extraction and usage in NLP tasks.
- Investigate where the context vector is located within transformer architectures.
  - Explore how self-attention mechanisms, hidden states, and intermediate layers contribute to the formation of context vectors.
- Determine whether the final layer or earlier layers (2nd/3rd) provide a more meaningful context representation.
  - In BERT-based models, the last hidden state may be overly fine-tuned, while intermediate layers might capture more generalizable contextual information.
  - Compare context vectors extracted from different layers to identify the optimal representation.
- Examine the role of context vectors in NLP downstream tasks such as next-word prediction, sentence similarity, and text classification.
  - Explore how these vectors influence decision-making in transformer models.

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
