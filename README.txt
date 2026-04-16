Intakes different filetypes to run NLP analysis and provides analysis including sentiment scores, topic modeling, sentiment based topics, sentiment based summaries and visualizations. Main use case is for Excel spreadsheets with survey answers. Will run analysis on each column(question) separately.

Instructions:
1. Download requirements
2. Save HF_TOKEN in .env
3. Run  python -m streamlit streamlit_app.py

Note: Deploys locally hence processing speed based on hardware. Added parallelization so now code works much faster given sufficient RAM.
