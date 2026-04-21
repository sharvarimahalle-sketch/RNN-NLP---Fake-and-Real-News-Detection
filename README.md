# RNN-NLP---Fake-and-Real-News-Detection
📌 Project Description
This project uses Recurrent Neural Networks (RNN) to detect whether a news article is fake or real. With the rise of misinformation on social media, this model helps identify fraudulent news content automatically. The model was trained on a dataset of 44,898 news articles and achieved an impressive 99.27% accuracy in classification.

🛠️ Tools & Technologies
Python - Programming Language
TensorFlow/Keras - Deep Learning Framework
NLTK - Natural Language Processing
Pandas & NumPy - Data Handling
Matplotlib & Seaborn - Visualization


📊 What I Did
1. Data Preprocessing
Cleaned text data by removing special characters, URLs, and numbers
Converted all text to lowercase
Removed stopwords (common words like "the", "is", etc.)
Applied lemmatization to normalize words

2. Text Tokenization
Tokenized news articles into sequences of words
Created a vocabulary of 10,000 most common words
Padded sequences to a fixed length of 500 tokens

3. Model Building
Built a Bidirectional LSTM model (a type of RNN)
Used GloVe 100-dimensional embeddings for word representation
Added dropout layers to prevent overfitting
Model architecture:
-Embedding Layer
-Bidirectional LSTM (128 units)
-Dense layers with dropout
-Output layer with sigmoid activation

4. Training & Testing
Split data: 80% training, 20% testing
Trained the model using binary cross-entropy loss
Used Adam optimizer for training

5. Model Evaluation
Evaluated performance using accuracy, precision, and recall
Generated confusion matrix to visualize results

🚀 Outcome
✅ Accuracy: 99.27%
✅ Precision: 99.24%
✅ Recall: 99.26%
The model successfully classifies fake and real news with near-perfect accuracy, making it highly reliable for detecting misinformation.

 Model Performance
 <img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/b4f29a5a-1ed9-4bf6-82de-fc7d5024d601" />

 Key Learnings
-- Gained hands-on experience with deep learning for NLP
-- Learned how to preprocess text data effectively
-- Understood the power of LSTM networks for sequence data
-- Achieved production level accuracy in a classification task

🔗 Connect with Me
LinkedIn: www.linkedin.com/in/sharvarimahalle
Email: sgmahalle23@gmail.com
