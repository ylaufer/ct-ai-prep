# CT-AI Prep Roadmap


## Run Locally

```bash
git clone https://github.com/ylaufer/ct-ai-prep.git
cd ct-ai-prep
python -m venv .venv
source .venv/Scripts/activate   # or . .venv/bin/activate on macOS/Linux
pip install -r requirements.txt


## ISTQB Certified Tester AI Testing (CT-AI) – Full Syllabus Coverage

This repo is organized to align 100% with the official CT-AI syllabus (v1.0). Below is a mapping of each syllabus chapter with its corresponding notebook content.

### ✅ Syllabus Chapter Mapping

| Chapter | Title                                           | Covered In               |
|---------|-------------------------------------------------|---------------------------|
| 1       | Introduction to AI                              | Week 1                   |
| 2       | Fundamentals of AI                              | Week 1                   |
| 3       | Testing AI-based Systems                        | Week 1                   |
| 4       | Quality Characteristics for AI-based Systems    | Week 2                   |
| 5       | ML Fundamentals and Training Data               | Week 2                   |
| 6       | ML Model Algorithms                             | Week 3                   |
| 7       | ML Model Performance Metrics                    | Week 3                   |
| 8       | Testing ML Models                               | Week 3                   |
| 9       | Test Environments and Tools                     | Week 4                   |
| 10      | Explainable AI and Ethics                       | Week 4                   |
| 11      | AI Lifecycle and Continuous Testing             | Week 5                   |
| 12      | Using AI for Testing                            | Week 5 & Week 6          |

### 📈 Visual Maps by Chapter (Objectives + Notebooks)
Each chapter includes a mindmap-style visual that summarizes:
- Main learning objectives
- Real-world examples
- Link to Jupyter notebook

**[👉 Visual Maps Folder](notebooks/_visual-maps)**

For each chapter, the naming follows: `map_chapter_<number>_<topic>.png`

---

### 🔧 Chapter 9 CI/CD Recommendation

**Enhancement for Test Environments and Tools:**

You can further enrich Chapter 9 by integrating a real CI/CD pipeline setup:
- Use **GitHub Actions** or **GitLab CI** to run model evaluation scripts
- Include integration with testing tools like `pytest`, `great_expectations`, or `DeepEval`
- Automate evaluation of fairness, accuracy, and explainability using your notebooks as job steps
