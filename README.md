# Intrusion Detection System using Machine Learning

## 📌 Overview
This project builds a machine learning-based Intrusion Detection System using the NSL-KDD dataset to classify network traffic as normal or attack.

## ⚙️ Tech Stack
- Python
- Pandas
- Scikit-learn
- Google Colab

## 📊 Dataset
- NSL-KDD dataset
- Contains labeled network traffic data for intrusion detection

## 🔧 Project Workflow
1. Data Loading
2. Data Preprocessing
3. Encoding categorical features
4. Feature scaling
5. Model training
6. Model evaluation

## 🤖 Models Used
- Logistic Regression
- Weighted Logistic Regression
- Random Forest Classifier

  ## 📊 Model Performance Comparison

| Model               |Accuracy | Precision (Attack)   | Recall (Attack) |
|------|--------|------------------|----------------   |
| Logistic Regression | 0.76       |    0.93           |     0.62 |
| Weighted Logistic   | 0.76       |    0.92           |     0.64 |
| Random Forest       | 0.77       |    0.97           |     0.62 |

## 📊 Results Visualization

### Confusion Matrix
![Confusion Matrix](confusion_matrix.png)

## 📈 Results
Random Forest achieved:

• Accuracy: 77%
• Precision (Attack): 97%
• Recall (Attack): 62%

The model demonstrated excellent precision in identifying malicious traffic while highlighting the importance of improving recall to reduce missed attacks.

## 🧠 Key Insight
There is a tradeoff between precision and recall. While the model is highly accurate in detecting attacks, improving recall is critical in cybersecurity applications to avoid missing threats.

## ▶️ How to Run
1. Open the notebook in Google Colab
2. Upload:
   - KDDTrain+.txt
   - KDDTest+.txt
3. Run all cells

## 🚀 Future Improvements
- Improve recall using advanced models like XGBoost
- Build real-time intrusion detection system
- Deploy using Streamlit

## 📌 Author
Rayyan Waheed
