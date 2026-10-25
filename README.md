# 🛡️ SMS Shield AI — Intelligent SMS Spam Detection

An AI-powered SMS spam detection web application that uses a deep learning LSTM model to classify text messages as **Spam** or **Ham (Legitimate Message)**.

SMS Shield AI provides a simple, interactive interface where users can enter an SMS message and receive a prediction with a confidence score.

## 🚀 Live Demo

🌐 **Live Application:** https://sms-shield-ai.onrender.com

💻 **GitHub Repository:** https://github.com/darsanipriya-13/sms_shield_ai.git

> Replace the placeholder URLs above with your actual Render deployment URL and GitHub repository URL.

## 📌 Project Overview

Unwanted SMS messages can contain misleading offers, fraudulent links, and spam content. Manually identifying these messages can be difficult.

SMS Shield AI uses Natural Language Processing (NLP) and a Long Short-Term Memory (LSTM) neural network to analyze message text and predict whether a message is spam or legitimate.

The project combines a trained deep learning model with a Gradio-based web interface to make SMS classification accessible through a browser.

## ✨ Key Features

- **AI-Powered Classification:** Predicts whether an SMS message is Spam or Ham.
- **LSTM Deep Learning Model:** Uses a recurrent neural network architecture for text classification.
- **Text Preprocessing:** Cleans and normalizes input messages before prediction.
- **Tokenization:** Converts text into numerical sequences using a saved tokenizer.
- **Sequence Padding:** Standardizes input length before passing messages to the model.
- **Confidence Score:** Displays the model's prediction score.
- **Interactive Web Interface:** Provides an easy-to-use interface built with Gradio.
- **Cloud Deployment:** Accessible online through Render.

## 🧠 How It Works

1. **Input:** The user enters an SMS message.
2. **Preprocessing:** The message is converted to lowercase and cleaned.
3. **Tokenization:** The saved tokenizer converts words into numerical sequences.
4. **Padding:** The sequence is padded to the expected input length.
5. **Prediction:** The trained LSTM model processes the input.
6. **Classification:** The model's output is used to classify the message as Spam or Ham.
7. **Result:** The interface displays the predicted category and confidence score.

## 🏗️ System Workflow

```text
          User Enters SMS
                 |
                 v
       Text Preprocessing
                 |
                 v
      Tokenization and Padding
                 |
                 v
       Trained LSTM Model
                 |
                 v
       Prediction Probability
                 |
                 v
       Spam or Ham Result
                 |
                 v
        Gradio Web Interface
```

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| TensorFlow / Keras | Deep learning model development and inference |
| LSTM | Sequence-based text classification |
| NLP | SMS text preprocessing |
| NumPy | Numerical operations |
| Pickle | Loading the saved tokenizer |
| Gradio | Interactive web application |
| Render | Cloud deployment |
| Git and GitHub | Version control and source code hosting |

## 📂 Project Structure

```text
sms_shield_ai/
│
├── app.py
├── requirements.txt
├── spam_lstm_model.keras
├── tokenizer.pkl
├── .python-version
└── README.md
```

## ⚙️ Run the Project Locally

### Prerequisites

- Python 3.12
- pip package manager
- Git

### 1. Clone the Repository

```bash
git clone https://github.com/darsanipriya-13/sms_shield_ai.git
```

### 2. Navigate to the Project Directory

```bash
cd sms_shield_ai
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Application

```bash
python app.py
```

Open the local Gradio URL displayed in your terminal.

**Note:** Keep `spam_lstm_model.keras` and `tokenizer.pkl` in the expected project directory. Use the TensorFlow version compatible with your trained model and deployment environment.

## 🧪 Example Predictions

**Example 1 — Potential Spam**

Input:
```text
Congratulations! You have won a free prize.
Claim your reward now!
```

Expected category: Spam

**Example 2 — Normal Message**

Input:
```text
Hi, I will reach home at 6 PM. See you soon.
```

Expected category: Ham

*These are illustrative examples. Actual results depend on the trained model.*

## 🎯 Project Objectives

- Apply deep learning to a real-world text classification problem.
- Understand NLP preprocessing, tokenization, and sequence padding.
- Develop an LSTM-based classification pipeline.
- Integrate a trained model into an interactive web application.
- Deploy a machine learning application to a cloud hosting platform.

## 🔮 Future Enhancements

- Improve classification performance with additional training data.
- Evaluate the model using precision, recall, F1-score, and a confusion matrix.
- Add batch SMS classification.
- Improve handling of suspicious URLs and phishing-related message patterns.
- Enhance model explainability and user feedback.
- Add multilingual SMS support.

## ⚠️ Disclaimer

SMS Shield AI is an educational machine learning project. Predictions may be incorrect, and the confidence score is not a guarantee that a message is safe or malicious. Avoid clicking suspicious links or sharing sensitive information based solely on the model's prediction.

## 👩‍💻 Author

**Darsani Priya RJ**

Third-Year Computer Science and Engineering Student

Interests: Artificial Intelligence, Machine Learning, Deep Learning, Natural Language Processing, and Software Development.

## ⭐ Support

If you find this project interesting, consider starring the repository and sharing your feedback.

---

**Built with Python, Deep Learning, and Gradio.**
