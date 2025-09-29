# Goolegle_Search_Analysis_Project
This project uses the pytrends library to analyze Google search trends. It shows keyword popularity by country and over time with charts and interactive world maps, and supports multi-keyword comparisons using Matplotlib, Seaborn, and Plotly.
A Jupyter Notebook project to explore and visualize Google search trends.  
It uses the `pytrends` library to fetch keyword interest data and display insights such as top countries, global heatmaps, time-series plots, and keyword comparisons.

---

## 🚀 Features
- Fetch Google Trends data programmatically using **pytrends**  
- Show **country-wise interest** with bar charts  
- Generate an **interactive world map (choropleth)**  
- Plot **time-series keyword trends**  
- Compare **multiple keywords** on the same chart  
- Export results to **CSV** for further analysis  

---

## 🛠️ Requirements
- Python 3.10+
- Jupyter Notebook / JupyterLab  
- Libraries:  
  - `pytrends`  
  - `pandas`  
  - `matplotlib`  
  - `seaborn`  
  - `plotly`  
  - `requests`  

(See `requirements.txt` for easy installation.)

---

## 📦 Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/google-trends-analysis.git
cd google-trends-analysis

# create virtual environment (recommended)
python -m venv venv
source venv/bin/activate    # macOS/Linux
venv\Scripts\activate       # Windows

# install requirements
pip install -r requirements.txt


Usage

Launch Jupyter Notebook:

jupyter notebook Google_search_analysis_project.ipynb


Edit the keyword(s) in the notebook.
Example:

kw_list = ["Python", "Java", "C++"]


Run the cells step by step to:

Fetch Google Trends data

Visualize interest by region

Plot time-series trends

Compare multiple keywords

Save outputs as CSV or images for later use.

📂 Notebook Structure

Setup: Install/import libraries, define keywords

Fetch Data: Build pytrends payload, handle retries

Country-wise Interest: Tabular + bar plot

World Map: Interactive choropleth

Time-series Interest: Line chart

Keyword Comparison: Multi-line comparison plot

⚠️ Notes & Limitations

Rate limiting: Google may block frequent requests. Use delays or backoff logic if errors occur.

Country names: Ensure they map correctly to ISO codes for choropleth maps.

Interactive plots: Work best in Jupyter; save static images with kaleido if needed.

🔮 Future Improvements

Add a CLI or script version for automation

Support custom date ranges and categories

Improve map robustness with ISO country code normalization

Deploy as a dashboard with Streamlit or Dash

📜 License

This project is licensed under the MIT License.
You are free to use, modify, and distribute it with attribution.

🙌 Acknowledgements

Pytrends
 for Google Trends API wrapper

Matplotlib
, Seaborn
, Plotly
 for visualization
