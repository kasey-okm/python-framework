# CORD-19 Metadata Analysis & Streamlit App

This project analyzes the CORD-19 metadata dataset and presents findings through visualizations and a simple Streamlit web application.

## Assignment Overview

- **Dataset:** `metadata.csv` from the CORD-19 research challenge ([Kaggle link](https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge))
- **Tools:** Python, pandas, matplotlib, seaborn, wordcloud, Streamlit, Jupyter Notebook

## Steps Completed

1. **Install and Import Libraries:**  
   All required packages are installed and imported.

2. **Data Loading:**  
   The `metadata.csv` file is loaded into a pandas DataFrame.

3. **Data Exploration:**  
   - Displayed shape, info, and summary statistics.
   - Checked for missing values.

4. **Data Cleaning:**  
   - Dropped rows with missing `title` or `publish_time`.
   - Filled missing abstracts.
   - Converted `publish_time` to datetime and extracted year.
   - Added abstract word count.

5. **Analysis & Visualization:**  
   - Counted papers by year.
   - Identified top journals.
   - Found frequent words in titles.
   - Plotted publications by year, top journals, word cloud, and paper counts by source.

6. **Streamlit App:**  
   - Interactive app with year range slider.
   - Displays all visualizations and sample data.

## How to Run

1. **Jupyter Notebook:**  
   Open `week8-1.ipynb` and run all cells for step-by-step analysis.

2. **Streamlit App:**  
   Save the Streamlit code in `streamlit_app.py` and run:
   ```
   streamlit run streamlit_app.py
   ```

## Findings

- Most publications were in 2020 and 2021.
- Top journals include [see notebook output].
- Common title words: [see notebook output].
- Main sources: [see notebook output].

## Reflection

This assignment provided hands-on experience with data cleaning, analysis, visualization, and web app development. Key challenges included handling missing data and ensuring clear, meaningful visualizations. Streamlit made it easy to share interactive results.

## Repository Structure

- `week8-1.ipynb` — Main analysis notebook
- `streamlit_app.py` — Streamlit web application
- `README.md` — Project overview and instructions

## License

This project is for educational purposes.# python-framework