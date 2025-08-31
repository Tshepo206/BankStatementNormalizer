# 🏦 Bank Statement Normalizer

[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white)](https://streamlit.io/)
[![Python](https://img.shields.io/badge/Python-3.13-blue?logo=python&logoColor=white)](https://www.python.org/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](./LICENSE)
[![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?logo=scikit-learn&logoColor=white)](https://scikit-learn.org/stable/)
[![GitHub Repo stars](https://img.shields.io/github/stars/Tshepo206/BankStatementNormalizer?style=social)](https://github.com/Tshepo206/BankStatementNormalizer/stargazers)

Normalize messy bank statements → Clean, structured CSVs + insights.  
Built with **Python, Pandas, Scikit-learn, and Streamlit** to showcase practical data engineering.

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
source .venv/bin/activate    # On Mac/Linux
# OR
.venv\Scripts\activate       # On Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the Streamlit app
streamlit run streamlit_app.py --server.port 8502
