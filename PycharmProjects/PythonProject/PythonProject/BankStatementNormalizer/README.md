# 🏦 Bank Statement Normalizer

A Streamlit-based web application that helps **normalize messy bank statement data** into a clean, structured format (CSV).  
Built with **Python, Pandas, Scikit-learn, and Streamlit**, this tool is designed to showcase practical **AI + Finance coding projects**.

---

## 📸 Screenshot

![App Screenshot](images/app.png)

---

## 🚀 Quick Start

Follow these steps to set up and run the project locally:

```bash
# 1. Clone the repository
git clone https://github.com/Tshepo206/BankStatementNormalizer.git
cd BankStatementNormalizer

# 2. Create and activate a virtual environment
python -m venv .venv
source .venv/bin/activate   # On Mac/Linux
# OR
.venv\Scripts\activate      # On Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the Streamlit app
streamlit run streamlit_app.py --server.port 8502