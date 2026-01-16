
---

# 🧠 Agentic AI Data Cleaning Assistant

An autonomous and intelligent **data cleaning agent** that leverages **OpenAI GPT** and **LangChain** for reasoning, and integrates **ML-based preprocessing and feature engineering** for scalable data refinement — all delivered through an interactive **Streamlit** interface.

---

## 💼 Business Use Case

Organizations deal with messy datasets containing:

* Inconsistent formatting (e.g., country names, income levels)
* Missing values, typos, and noisy text
* Unstructured categorical or numerical fields

This AI agent streamlines the cleaning process by:

* Automatically classifying and transforming fields
* Using GPT for intelligent suggestions on ambiguous entries
* Applying ML preprocessing and feature engineering techniques

---

## 🚀 Features

* ✅ Upload raw customer data in `.csv` format
* ✅ Clean and standardize inconsistent entries (e.g., “USA”, “U.S.A.” → “United States”)
* ✅ GPT-powered logic for ambiguous values
* ✅ Feature engineering and preprocessing modules
* ✅ Download cleaned dataset with transformations applied

---

## 📂 Updated Project Structure

```
AGENTS_AI_DATA_CLEANING_LANGCHAIN_OPENAI/
├── .github/                          # GitHub configuration (if any)
├── app/
│   └── app.py                        # Streamlit UI
├── data/
│   └── raw/
│       └── customers_dirty.csv       # Sample dirty dataset
├── src/
│   ├── __pycache__/
│   ├── feature_engineering.py        # Feature transformation logic
│   ├── inference.py                  # GPT + rule-based cleaning
│   ├── model_training.py             # Optional ML model training
│   ├── preprocessing.py              # Data cleaning and preprocessing functions
│   └── utils.py                      # Utility functions (load, save, etc.)
├── Dockerfile                        # Containerization
├── LICENSE
├── README.md
└── requirements.txt                  # Python dependencies
```

---

## 🧠 Technologies Used

| Tool             | Purpose                                             |
| ---------------- | --------------------------------------------------- |
| **LangChain**    | Framework to manage GPT and tool-based reasoning    |
| **OpenAI GPT**   | Language understanding and contextual corrections   |
| **Pandas**       | Data manipulation and cleaning                      |
| **Scikit-learn** | Preprocessing, transformation, and ML utilities     |
| **Streamlit**    | Interactive web app for uploading and cleaning CSVs |
| **Docker**       | For reproducible deployment                         |

---

## 🛠️ How to Run

### 1. Clone the repo:

```bash
git clone https://github.com/amitkharche/agents_agentic_email_assistant_langchain_openai.git
cd agents_agentic_email_assistant_langchain_openai
```

### 2. Install dependencies:

```bash
pip install -r requirements.txt
```

### 3. Add your OpenAI API key:

Create a `.env` file with:

```env
OPENAI_API_KEY=your_openai_key
```

### 4. Launch the Streamlit app:

```bash
streamlit run app/app.py
```

---

## 💡 How It Works

1. **Upload CSV** with messy data
2. The app:

   * Applies **preprocessing rules**
   * Uses **feature engineering** for better transformations
   * Invokes **GPT (via LangChain)** for ambiguous corrections
3. Download the **cleaned and transformed dataset**

---

## 📬 Contact

* 💼 [LinkedIn](https://www.linkedin.com/in/amitkharche)
* ✍️ [Medium](https://medium.com/@amitkharche)
* 💻 [GitHub](https://github.com/amitkharche)

---
