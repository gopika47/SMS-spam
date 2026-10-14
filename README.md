# SMS Spam Detection Using LSTM

## Project Overview
This project uses deep learning to classify SMS messages as Spam or Ham (normal messages).

## Technologies Used
- Python
- TensorFlow and Keras
- Pandas and NumPy
- Scikit-learn
- Matplotlib and Seaborn

## Model Architecture
Embedding → LSTM → Dropout → Dense → Sigmoid

## Project Workflow
1. Load the SMS dataset.
2. Clean and preprocess the text messages.
3. Tokenize the text and apply padding.
4. Build an LSTM-based deep learning model.
5. Train and test the model.
6. Evaluate performance using accuracy, precision, recall, and F1-score.
7. Predict spam or ham for new messages.

## Results
- Testing Accuracy: 98.75%
- Precision: 92.45%
- Recall: 98.00%
- F1-score: 95.15%

## Dataset
[Kaggle SMS Spam Detection Dataset](https://www.kaggle.com/datasets/vishakhdapat/sms-spam-detection-dataset)
