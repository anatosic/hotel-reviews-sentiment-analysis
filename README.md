Hotel Reviews Sentiment Analysis (BERT vs. RoBERTa)
This project compares two pre-trained Transformer models (BERT and RoBERTa) fine-tuned for sentiment classification on hotel reviews.

It covers the full NLP workflow: data preprocessing, hyperparameter tuning, quantitative evaluation, qualitative error analysis, and layer-wise embedding visualization using TensorBoard.

📌 Quick Highlights
Goal: Classify hotel guest reviews as POSITIVE or NEGATIVE.

Dataset: 304 samples from the 17k Hotel Reviews Dataset.

Best Model: RoBERTa achieved 96.9% accuracy (vs. BERT's 93.7%), demonstrating faster convergence and tighter cluster separation in high-dimensional embedding space.

Key Challenge: Both models struggled with mixed-sentiment reviews (e.g., polite phrasing masking negative feedback).

🛠️ Tech Stack
Python, Hugging Face (transformers, datasets, evaluate), PyTorch, TensorBoard, Pandas, NumPy, Scikit-learn.

🚀 How to Run
1. Clone the repo:
git clone https://github.com/anatosic/hotel-reviews-sentiment-analysis.git 

2. Install dependencies:
pip install -q transformers datasets evaluate bertviz accelerate torch pandas numpy scikit-learn

3. Run hotel_sentiment_analysis.ipynb in Google Colab or Jupyter Notebook.
