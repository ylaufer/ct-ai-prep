# Week 02 – Quality Characteristics & Evaluation Metrics

This summary covers the key quality attributes and evaluation metrics used in AI systems, aligned with the CT-AI syllabus.

---

## 🧠 AI-Specific Quality Characteristics

| Quality Attribute | Description | Relevance |
|-------------------|-------------|-----------|
| **Accuracy** | How often the model is correct | General performance |
| **Robustness** | Stability under noisy, adversarial, or shifted data | Safety-critical systems |
| **Explainability** | Ability to understand why a model made a decision | Transparency, trust |
| **Fairness** | Ensuring outcomes are not biased against certain groups | Ethical, legal compliance |
| **Security** | Protection against adversarial attacks or model inversion | Cybersecurity-sensitive domains |
| **Data Privacy** | How data is handled, stored, and protected | GDPR, HIPAA, etc. |
| **Reproducibility** | Ability to reproduce results using the same pipeline | Research, regulatory needs |

---

## 📊 Key Evaluation Metrics

### Classification Metrics
| Metric | Formula | When to Use |
|--------|---------|-------------|
| **Accuracy** | (TP + TN) / Total | When classes are balanced |
| **Precision** | TP / (TP + FP) | When false positives are costly |
| **Recall** | TP / (TP + FN) | When false negatives are costly |
| **F1-score** | Harmonic mean of precision & recall | When balance is needed |
| **Confusion Matrix** | TP, FP, TN, FN | Basic visual breakdown |
| **ROC-AUC** | Area under the ROC curve | Good for probabilistic classifiers |

### Regression Metrics
| Metric | Description |
|--------|-------------|
| **MSE (Mean Squared Error)** | Penalizes large errors more |
| **MAE (Mean Absolute Error)** | More interpretable than MSE |
| **R² (R-squared)** | How much variance is explained by the model |

---

## ⚠️ When Accuracy is NOT Enough

Accuracy can be misleading when:
- You have **imbalanced classes** (e.g. 95% non-fraud)
- You care more about **specific types of error** (e.g. false negatives in cancer detection)

---

## 🧪 Best Practice

Always match your metric to:
- The **business goal** (e.g. minimize fraud losses)
- The **data type** (imbalanced? continuous?)
- The **risk type** (legal, ethical, financial)

---

📘 This summary prepares you for the evaluation metric notebooks and hands-on exercises this week.
