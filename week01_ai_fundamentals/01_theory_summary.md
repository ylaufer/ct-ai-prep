# Week 01 – AI Fundamentals & Machine Learning Concepts

This summary covers key theoretical concepts from the CT-AI syllabus related to AI systems, machine learning types, and foundational concepts like bias and variance.

---

## 🤖 Types of AI Systems

| Type | Description | Example |
|------|-------------|---------|
| Symbolic (Rule-based) | Based on logic and rules | Expert systems, Prolog |
| Sub-symbolic | Learns from data | Neural networks, SVMs |
| Hybrid | Combines both approaches | Self-driving cars (rules + learning) |

---

## 📊 Types of Machine Learning

| Type | Description | Example |
|------|-------------|---------|
| Supervised | Learns from labeled data | Spam detection, fraud detection |
| Unsupervised | Finds patterns in unlabeled data | Clustering customers |
| Reinforcement | Learns from actions and feedback (rewards) | Game-playing agents, robotics |

---

## 🔄 ML Lifecycle Phases

1. **Data Collection** – from real users or synthetic sources
2. **Data Preparation** – cleaning, formatting, transforming
3. **Model Training** – using algorithms like decision trees or neural nets
4. **Model Evaluation** – using metrics (accuracy, F1-score)
5. **Deployment & Monitoring** – in real systems, detecting drift
6. **Continuous Feedback Loop** – retraining as needed

---

## ⚖️ Bias, Variance & Model Generalization

- **Underfitting (High Bias)**:
  - Model is too simple
  - Poor on training *and* test data
- **Overfitting (High Variance)**:
  - Model memorizes training data
  - Good on training but poor on test
- **Generalization**:
  - The sweet spot: model performs well on unseen data

---

## 🧠 Key Terms

- **Label** – the correct answer (e.g., spam or not)
- **Feature** – input attribute (e.g., email length, sender)
- **Model** – mathematical representation trained on data
- **Loss Function** – quantifies prediction error during training

---

📘 *This summary prepares you for the hands-on exercises in this week’s folder. Refer to the Jupyter Notebooks for visual explanations and code examples.*