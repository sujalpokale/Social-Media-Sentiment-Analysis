# Social Media Sentiment Analysis

## 📖 Project Description
This project focuses on performing **sentiment analysis** on social media posts to classify text into **positive**, **negative**, or **neutral** sentiments. The goal is to understand public opinion and extract actionable insights from user-generated content.

The project includes:
- Text preprocessing using tokenization, lemmatization, and stop-word removal.
- Model training using both deep learning (LSTM) and traditional methods (SVM, Random Forest).
- Evaluation of models with accuracy, loss curves, and confusion matrices.
- A user-friendly interface using **Gradio** to interact with the trained model in real-time.

---

## ✅ Features
- **Data Preprocessing**: Clean and prepare raw text data for model training.
- **Modeling**: Train and compare multiple models including LSTM, SVM, and Random Forest.
- **Evaluation**: Measure model performance using metrics like accuracy and loss.
- **Interactive UI**: Use Gradio to allow users to input text and receive sentiment predictions.
- **Exportable Model**: Save the best-performing model for future use.

---

## 📂 Dataset

The dataset used in this project is the **Social Media Sentiment Dataset**. It contains labeled posts from various platforms classified into three sentiment categories.

### Dataset Link:
You can download the dataset here:  
[Social Media Sentiment Dataset](https://www.kaggle.com/datasets/your-dataset-link)  
> Replace the above link with your actual dataset location (Google Drive or Kaggle).

The dataset file used in this project is:  
`social_media_sentiment.csv`

---

## 🛠 Technologies Used

- **Python 3.12**
- **TensorFlow / Keras** – Deep learning framework for LSTM models
- **scikit-learn** – Traditional ML algorithms and evaluation tools
- **NLTK / spaCy** – Natural Language Processing tools for text cleaning
- **Pandas / NumPy** – Data manipulation and numerical operations
- **Gradio** – UI interface for easy model interaction
- **Google Colab** – Cloud-based environment for running the notebook

---

## 🚀 How to Run the Project

### 1. Clone the Repository
git clone https://github.com/yourusername/social-media-sentiment-analysis.git
cd social-media-sentiment-analysi
### 2. Upload the Dataset
Place social_media_sentiment.csv in the project folder or mount Google Drive if using Colab.
### 3. Install Required Libraries
  pip install -r requirements.txt

Alternatively, install libraries directly:
  pip install tensorflow scikit-learn pandas numpy nltk spacy gradio

### 4. Run the Notebook
  Open the notebook in Google Colab and execute all cells step by step.

### 5. Launch the Gradio UI
  The final cell will start a web interface where you can input text and view sentiment predictions.

## 📊 Model Performance

- LSTM achieved validation accuracy of around X% (modify after training).
- SVM and Random Forest achieved Y% and Z% respectively.
- Confusion matrices and classification reports are provided for deeper analysis
