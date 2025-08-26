
IP Assistant Prototype (v2) – Streamlit
=======================================

Files:
- ip_portfolio_template.xlsx  (sample IP portfolio with columns expected by the app)
- new_tm_filings_sample.csv   (sample 'new filings' feed to demo Trademark Watch)
- TM_License_Template_Placeholders.docx  (Word template used for contract generation)
- ip_assistant_app_v2.py      (the Streamlit app)

Run locally:
------------
pip install streamlit pandas python-docx rapidfuzz
streamlit run ip_assistant_app_v2.py

Email (optional):
-----------------
Use a trusted SMTP (Office 365, Gmail with App Password). Enter SMTP settings in the app to send renewal reminders.

Notes:
------
- Trademark watch uses a CSV feed for demo; replace with official registry ingestion for production.
- Generated agreements are drafts; legal review required.
