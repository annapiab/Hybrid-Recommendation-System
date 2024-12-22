# Hybrid Product Recommendation System

## Summary
This project implements a hybrid recommendation system for e-commerce, combining content-based filtering (using TF-IDF and BERT embeddings) and collaborative filtering. The system provides an interactive interface for users to search products and receive personalized recommendations, balancing relevance and diversity to enhance user experience.

## Evaluation

The system evaluates recommendations based on two metrics:
- **Average Similarity**: Measures how relevant the recommendations are to the selected product.
- **Diversity**: Ensures that recommendations include a variety of products and brands.

These metrics are displayed alongside recommendations during the interactive session.

## Future Work

- Improve the system to achieve higher diversity scores by refining the diversification function.
- Ensure diverse representation of manufacturers in recommendations.
- Explore alternative embedding models like **RoBERTa** or domain-specific transformers for more nuanced content-based similarity.
- Refine feature engineering and preprocessing methods to capture more intricate relationships between products.

---

### Acknowledgments

This project was built using the Amazon Products dataset and leverages powerful libraries such as:
- **scikit-learn** for TF-IDF and collaborative filtering.
- **Hugging Face Transformers** for BERT-based embeddings.
- **pandas** and **numpy** for data manipulation.
- **matplotlib** for data visualization.

For questions or suggestions, feel free to contact me.
