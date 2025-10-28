# Understanding-Text-Classification-Decisions-on-Twitter-Data-through-SHAP-Analysis
This project focuses on classifying Twitter posts into three categories — neutral, offensive, and hate speech — using ModernBERT, a transformer-based language model optimized for modern NLP tasks.

After fine-tuning the model on a balanced dataset of tweets, the project applies SHAP (SHapley Additive exPlanations) to interpret model predictions.
SHAP visualizations reveal which words or phrases contribute most to the model’s decision for each class, allowing deeper insight into how the model distinguishes between neutral and harmful content.

### Technologies Used
- Python, PyTorch, Hugging Face Transformers
- Datasets library
- SHAP for explainability
- Scikit-learn for metrics and data preprocessing
