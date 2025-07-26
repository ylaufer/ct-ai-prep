# Week 04 – Explainability, Ethics & AI-Driven Testing

This summary covers the final topics from the CT-AI syllabus: explainability tools, ethics, regulatory principles, and how AI can be used to test software.

---

## 🧠 1. Explainable AI (XAI)

| Type | Description | Example Tools |
|------|-------------|---------------|
| **Global** | Understand the model as a whole | Feature importance, partial dependence |
| **Local** | Explain one specific prediction | LIME, SHAP, anchor explanations |

**Use Cases**:
- Healthcare (must justify decisions)
- Finance (credit scoring)
- Legal compliance (GDPR “right to explanation”)

---

## 🛠️ Common XAI Tools

- **LIME**: Creates interpretable surrogate models for local predictions
- **SHAP**: Based on game theory; assigns contribution values to each feature
- **Saliency maps**: Used for image models to show pixel-level importance
- **Feature importance**: Built-in support in models like Random Forest

---

## ⚖️ 2. Ethics, Fairness, and AI Governance

| Concern | Description |
|---------|-------------|
| **Bias & Discrimination** | Unequal treatment of groups (race, gender, age) |
| **Transparency** | Stakeholders can understand model logic |
| **Accountability** | Humans responsible for AI decisions |
| **Traceability** | Logging model behavior and training history |
| **Privacy** | Ensuring data confidentiality (GDPR, HIPAA) |

**Regulations & Guidelines:**
- GDPR (Europe)
- EU AI Act
- IEEE Ethically Aligned Design
- OECD AI Principles

---

## 🤖 3. Using AI to Improve Testing

AI can help:
- Predict defect-prone modules
- Optimize test selection
- Generate test cases (model-based or LLM-based)
- Detect anomalies in test results

**Common Techniques:**
- Supervised learning on historical defect/test data
- Clustering for test grouping
- LLM prompting to generate test scenarios

---

📘 This week will walk you through explainability (LIME), ethical evaluation, and test optimization with AI support.
