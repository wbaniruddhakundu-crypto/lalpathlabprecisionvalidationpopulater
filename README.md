# Universal 5-Day Inter-Run Precision

## Features
- Upload one or more instrument PDF reports and an Excel precision template.
- Detect assay headings dynamically rather than relying on a fixed analyte whitelist.
- Group results by actual report date and QC level.
- Select up to five observations closest to the group median for each analyte/date/level.
- Preserve previous days by uploading the latest populated workbook on subsequent runs.
- Include a raw extraction audit and upload summary in the output workbook.
- Enter **Lab Name** and **Place / Location** in the Streamlit interface; these are printed on every analyte worksheet.

## Run locally

```bash
pip install -r requirements.txt
streamlit run app.py
```

Deploy the repository on Streamlit Community Cloud with `app.py` as the main file.
