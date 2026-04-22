# GPT
Academic project focused on data analysis and AI model evaluation
# AI Model Comparison: GPT-3.5 vs GPT-4 for Emotion Detection

## 📌 Overview
This project focuses on analyzing and comparing the performance of two AI models — GPT-3.5 and GPT-4 — in the task of emotion detection in text data.

The goal was to evaluate which model provides more accurate and reliable classification of emotions and to understand the impact of data quality and prompt design on model performance.

---

## 🎯 Objectives
- Compare GPT-3.5 and GPT-4 in text emotion classification
- Analyze the impact of dataset quality on results
- Evaluate different prompt engineering approaches
- Measure model performance using standard metrics

---

## 📊 Data
The analysis was performed using multiple publicly available datasets:
- Twitter datasets (emotion & sentiment classification)
- Kaggle datasets

Key steps:
- Data cleaning and preprocessing
- Removing duplicates
- Balancing datasets
- Normalizing labels

---

## ⚙️ Methodology

### 1. Data Processing
- Tokenization and text normalization
- Removing noise and inconsistencies
- Dataset balancing

### 2. Model Interaction
- API-based interaction with:
  - GPT-3.5
  - GPT-4
- Multiple prompt strategies tested

### 3. Prompt Engineering
Different prompt formats were tested to improve accuracy:
- Standard classification prompts
- Structured prompts (forcing numeric output)

### 4. Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score

---

## 🧪 Results & Insights
- GPT-4 consistently outperformed GPT-3.5 in most datasets
- Prompt design had a significant impact on performance
- Data quality issues (incorrect labels, imbalance) strongly affected results
- Forcing structured output (e.g. numeric labels) improved classification consistency

---

## ⚠️ Challenges
- Noisy and incorrectly labeled datasets
- Model inconsistencies in output formatting
- Handling unexpected responses from API
- Cost and API limitations

---

## 🛠️ Technologies Used
- Python
- OpenAI API
- Pandas / NumPy
- Jupyter Notebook

---

## 📈 Key Takeaways
- Data quality is critical for reliable AI analysis
- Prompt engineering plays a major role in model performance
- GPT-4 shows better contextual understanding and stability
- AI outputs require validation and normalization in real-world use

---
