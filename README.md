# FairAI: Bias Detection and Fairness Analysis Web Tool

FairAI is a web-based application designed to detect, evaluate, and visualize fairness in machine learning models. It helps users assess algorithmic bias, understand disparities in predictions across sensitive groups (like gender or race), and make informed decisions to build ethical AI systems.

---

## Features

* **Upload Datasets** (CSV format)
* **Fairness Metrics Computation**

  * Demographic Parity Difference (DPD)
  * Equalized Odds Difference
  * True Positive Rate Difference
  * Selection Rate Difference
* **Model Training** (Logistic Regression, Random Forest)
* **Visualizations** of bias and performance
* ⚖**Sensitive Attribute Selection** (e.g., gender, age)
* **Preprocessing Tools** (missing value handling, encoding)

---

## How to Run

### Prerequisites

* Python 3.8+
* pip

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/FairAI.git
cd FairAI

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py
```

---

## Tech Stack

| Component      | Technology    |
| -------------- | ------------- |
| Frontend       | Streamlit     |
| Backend        | Python        |
| ML Algorithms  | Scikit-learn  |
| Fairness Tools | Fairlearn     |
| Visualization  | Matplotlib    |
| Data Handling  | Pandas, NumPy |

---

## Example Use Case

**Problem:** Predict whether a candidate will be hired based on gender, experience, and qualification.

**Insight with FairAI:** Model favors a particular gender. Fairness metrics reveal demographic disparity → User decides to retrain the model or apply mitigation.

---

## Future Scope

* Add bias mitigation techniques
* Export fairness reports (PDF/CSV)
* Integrate model explanations (e.g., SHAP)
* User authentication and session tracking

---

## License

MIT License

---

## Acknowledgements

* [Fairlearn](https://fairlearn.org/)
* [Scikit-learn](https://scikit-learn.org/)
* [Streamlit](https://streamlit.io/)

---
# View Full Colab Notebook
https://colab.research.google.com/drive/1Dm3sNSJts_MJhq8O91-EQA6KpRyg8wwo
