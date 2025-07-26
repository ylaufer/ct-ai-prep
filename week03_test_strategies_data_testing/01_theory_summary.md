# Week 03 – Test Strategies, Data Quality & Metamorphic Testing

This summary covers key CT-AI topics around how to test AI systems when outputs are uncertain or data is unstable.

---

## 🧪 1. Test Strategies for AI

| Strategy | Description |
|----------|-------------|
| **Black-box testing** | No knowledge of model internals; test based on inputs/outputs |
| **White-box testing** | Access to model code/architecture for internal validation |
| **Risk-based testing** | Focus on testing features with highest impact or uncertainty |
| **Adversarial testing** | Input noise or perturbations to check model stability |
| **Oracle Problem** | When expected output is unknown or undefined (common in AI) |

---

## 📦 2. Data Quality Challenges

| Issue | Description |
|-------|-------------|
| **Bias** | Model learns patterns that favor or penalize certain groups |
| **Drift** | Data distribution changes over time (input or concept drift) |
| **Noise** | Random errors in features or labels |
| **Imbalance** | Some classes are much more frequent than others |
| **Data Leakage** | Information from test data appears in training data |

**Mitigation Techniques:**
- Data validation frameworks (e.g., Great Expectations, Deepchecks)
- EDA (Exploratory Data Analysis) for bias detection
- Rebalancing datasets (e.g., oversampling, undersampling)

---

## 🔁 3. Metamorphic Testing

**Definition**: A testing technique used when no test oracle is available.  
Instead of checking a single expected output, we define **relations between inputs and outputs**.

### 🧪 Example:
If `translate(English → French)` and then `translate(French → English)`, the result should be close to the original.

**Common Metamorphic Relations:**
- Input transformation: scaling, rotation, shuffling
- Invariance: results shouldn’t change if input order is shuffled
- Monotonicity: increasing input shouldn't decrease output

---

## 🧠 Summary Tips

- When output isn't deterministic or test oracle is missing → use **metamorphic testing**
- When testing for fairness → analyze **bias** and **drift**
- When working with small or skewed datasets → **pairwise** or **stratified sampling** can help

📘 This week’s exercises will cover EDA, metamorphic test design, and data strategy.
