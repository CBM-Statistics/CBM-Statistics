# Neural Networks and Deep Learning Workshop

> A comprehensive one-day workshop covering deep learning fundamentals and hands-on applications in image classification and time series forecasting.

---

## 📋 Workshop Overview

This workshop is split into two sessions, each led by a dedicated team of instructors:

| Session | Time | Duration |
|---|---|---|
| Morning: Introduction to Deep Learning | 08:30 – 12:00 | 3.5 hours |
| Afternoon: Hands-on Deep Learning Applications | 13:00 – 16:30 | 3.5 hours |

---

## 🕐 Schedule

### Registration
| Time | Activity |
|---|---|
| 07:45 – 08:30 | Registration & Badge Pickup |

### Morning Session — Introduction to Deep Learning (08:30–12:00)
**Instructor:** Dr Konstantinos Makantasis — Department of Artificial Intelligence, University of Malta

| Time | Module | Focus |
|---|---|---|
| 08:30 – 10:30 | **Foundations of Neural Networks** | Learning framework, historical evolution, feedforward architectures, activation functions (ReLU and variants), regularisation techniques (norm penalties, early stopping, dropout), optimisation challenges, parameter initialisation, learning rates, batch normalisation |
| 10:30 – 11:00 | Break | |
| 11:00 – 12:00 | **Deep Learning: Specialised Architectures, Metrics, and Implementation Methodology** | Advanced loss functions (contrastive, triplet margin), evaluation metrics (R², precision-recall, F1), autoencoders, CNNs, tensor neural networks, LSTMs, hyperparameter tuning, debugging |

### Afternoon Session — Hands-on Deep Learning Applications (13:00–16:30)
**Instructors:** Bilal Kurban & Roxanne Spiteri — Department of Statistics, Central Bank of Malta

| Time | Module | Focus |
|---|---|---|
| 13:00 – 13:15 | **Introduction & Setup** | Verify installations, load datasets, TensorFlow recap |
| 13:15 – 14:30 | **Part 1: Handwritten Digit Recognition** | Neural network structure, training, and tuning for image data |
| 14:30 – 14:45 | Break | |
| 14:45 – 16:15 | **Part 2: RNN & LSTM for Time Series Forecasting** | Build RNN and LSTM models to forecast Malta's Foreign Trade indicators |
| 16:15 – 16:30 | **Wrap-up & Discussion** | Compare architectures, strengths & limitations, Q&A |

---

## 📖 Course Description

### Morning Session — Introduction to Deep Learning

Neural networks and deep learning represent a powerful subset of statistical learning algorithms that have revolutionised complex problem-solving across natural language processing, autonomous vehicles, and healthcare. Unlike conventional machine learning methods that rely on manual feature extraction, deep learning leverages multi-layered neural architectures capable of automatically discovering intricate patterns within large datasets.

Topics covered include:
- Mathematical foundations of the learning framework
- Historical evolution of neural networks
- Deep learning architectures: convolutional, recurrent, and tensor neural networks
- Loss functions, evaluation metrics, and hyperparameter tuning
- Debugging methodologies for training deep models

### Afternoon Session — Hands-on Practice

The practical component guides participants through two real-world applications:

**Part 1 — Handwritten Digit Recognition**

Using the [MNIST dataset](https://keras.io/api/datasets/mnist/) (60,000 training + 10,000 test images, 28×28 pixels), participants will:
- Normalise and prepare image data
- Build a Keras Sequential model with `Flatten`, `Dense` (ReLU), and `Softmax` output layers
- Compile with Sparse Categorical Cross Entropy loss and SGD optimiser
- Train with mini-batches, monitor validation loss, and evaluate on the test set
- Visualise predictions using a Confusion Matrix

**Part 2 — Time Series Forecasting (Malta's Foreign Trade)**

Using [Malta's Foreign Trade data](https://www.centralbankmalta.org/external-statistics) from the Central Bank of Malta, participants will:
- Preprocess time series with proper time indexing and MinMaxScaler normalisation
- Convert data into supervised format using a sliding window approach
- Apply a chronological train/test split to preserve temporal dependencies
- Build and compare Simple RNN and LSTM models
- Evaluate models using RMSE and MAE, plot residuals, and generate future forecasts

---

## 🎯 Learning Outcomes

After completing this workshop, participants will be able to:

- Explain the evolution and core principles of neural networks and deep learning
- Use Keras and TensorFlow to build, train, and evaluate neural network models
- Identify and configure key components: architectures, activation functions, loss functions, and hyperparameters
- Distinguish between major architectures (autoencoders, CNNs, LSTMs, transformers) and describe their applications
- Apply techniques for monitoring, tuning, and optimising deep learning models
- Set up isolated Python environments and install required libraries
- Build Feedforward Networks for classification and RNN/LSTM models for time series forecasting
- Select appropriate loss functions and metrics for different problem types
- Diagnose overfitting by monitoring training/validation curves and interpreting residuals
- Generate and plot recursive future forecasts with confidence intervals

---

## 💻 Software Requirements

Participants must bring a laptop with one of the following:

- **[Anaconda Distribution of Python](https://www.anaconda.com/download)** (recommended, local installation)
- **[Google Colab](https://colab.research.google.com/)** (web-based alternative, no installation required)

Key libraries used: `TensorFlow`, `Keras`, `Matplotlib`, `Seaborn`, `scikit-learn`

---

## 👥 Who Should Attend

This workshop is designed for:
- Graduate and undergraduate students
- Practitioners and researchers

**Prerequisites:** Basic to intermediate proficiency in Python programming.

---

## 🧑‍🏫 Instructors

### Dr Konstantinos Makantasis
*Lecturer, Department of Artificial Intelligence — University of Malta*

Dr Makantasis holds a Diploma in Computer Engineering and MSc and PhD degrees from the Technical University of Crete. In 2020, he was awarded the Marie Skłodowska-Curie Actions Individual Fellowship (Widening) for research on tensor-based machine learning for affect modelling. He is included in Stanford University's **World's Top 2% Scientists List (2023)**, with 23 journal articles and 49 peer-reviewed conference papers.

His research focuses on the intersection of machine and statistical learning, image and signal processing, and computer vision. He has collaborated with the KIOS Centre of Excellence (University of Cyprus), the Institute of Digital Games (University of Malta), and industry partners including EXUS (UK), 7Reasons (Austria), and Massive Entertainment-Ubisoft (Sweden).

🔗 [Personal Website](https://www.um.edu.mt/profile/konstantinosmakantasis)

---

### Bilal Kurban
*Senior Statistician, Central Bank of Malta*

Bilal is a seasoned data scientist and AI expert holding an M.Sc. in Data Science and a B.Sc. in Statistics. He previously led the Artificial Intelligence and Data Analysis Unit at the Turkish Statistical Institute, spearheading projects in big data analytics, machine learning, and AI-powered statistical tools.

His expertise covers data governance, business intelligence, and the integration of administrative data into official statistics. An internationally recognised professional, Bilal has contributed to UNECE workshops and published extensively on data collection methodologies and the use of administrative data in official statistics.

---

### Roxanne Spiteri
*Statistician, Statistics Department — Central Bank of Malta*

Roxanne is a machine learning enthusiast with a particular interest in the intersection of statistical theory and modern computational methods. She holds a BSc (Honours) in Mathematics, Statistics and Operations Research from the University of Malta. Her undergraduate dissertation, *"Identifying Cyberattacks using Machine Learning Techniques,"* applied Neural Networks and Variable Importance techniques to detect malicious network traffic in the field of anomaly and outlier detection.

---

## 📌 Logistics

| Detail | Info |
|---|---|
| Format | Classroom style |
| Max Capacity | 20 participants per workshop |
| Online Participation | Not available |
| Provided by Organisation | Tutor table, screens, Wi-Fi, electricity, pads, pens, water |
| Participants to Bring | Laptops with pre-installed software |
| Catering | Lunch + 2 coffee breaks |

> **Note:** Personal data (name, institution, passport/ID number) is collected upon registration. A passport or identification document must be presented on the day at the CBM premises.
