# GreenCart: Sustainable Shopping Recommendation System

## Overview
GreenCart is a NLP based project using pretrained BERT model that helps users make eco-conscious decisions by analyzing the product and recommending more sustainable alternatives. The system fine tunes the pretrained BERT to classify products based on their sustainability and suggests greener options using content-based recommendation techniques.

---

## Workflow
1. **Data**: Amazon eco friendly dataset from Kaggle
2. **Preprocessing**:
   - Selecting Useful features
   - Cleaning text data
3. **Lemmatization**: using Spacy library, language model: en_core_web_sm
4. **Tokenization**: using Berttokenizer pretrained model
5. **Model Training**: Functional API ANN model taking bert embadding as input
6. **Evaluation**: MAE, RMSE
7. **User Inference:
   - Query by product index:
     - If It's sustainable or not
     - similar sustainable products

---

## Tech Used
- **Languages**: Python
- **Libraries**: scikit-learn, pandas, NumPy, matplotlib, transformers
- **Models**: BERT
- **Recommendation**: Cosine Similarity (Content-Based Filtering)
- **Tools**: Jupyter Notebook, VS Code, Git

---

## License

This project is for educational and research purposes only.