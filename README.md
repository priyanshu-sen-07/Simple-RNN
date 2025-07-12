# 🎬 IMDB Movie Review Sentiment Analysis

<img src="Screenshot 2025-07-12 232448.png" width="700"/>

## 📖 Project Overview

This project uses Deep Learning (Simple RNN) to classify movie reviews from the IMDB dataset as **Positive** or **Negative**. It features a clean and interactive **Streamlit UI** that allows users to input a review and instantly receive sentiment feedback.

---

## 🧠 Model Architecture

- **Embedding Layer**: Turns words into dense vector representations.
- **Simple RNN Layer**: Learns sequential patterns in reviews.
- **Dense Output Layer**: Predicts sentiment using `sigmoid` activation.
- **Loss Function**: `binary_crossentropy`
- **Optimizer**: `adam`

---

## 📦 Technologies & Libraries Used

| Type            | Libraries/Tools Used                               |
|------------------|----------------------------------------------------|
| **Language**     | Python                                             |
| **Deep Learning**| `tensorflow==2.15.0`, `scikeras`, `keras`          |
| **Data Handling**| `pandas`, `numpy`, `scikit-learn`                  |
| **Visualization**| `matplotlib`, `tensorboard`                        |
| **Web UI**       | `streamlit`                                        |

---

## 🚀 How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/imdb-sentiment-analysis-rnn.git
cd imdb-sentiment-analysis-rnn
