📊 Data Extractor & Enrichment Tool

This Jupyter Notebook provides a comprehensive solution for extracting structured data from Excel files containing company information. It uses advanced NLP libraries to parse text and extract contacts, personal names, emails, phones, addresses, and job titles. The tool also enables enrichment of extracted data with email campaign results and merging of multiple datasets.

🚀 Features

    Entity extraction – Names, surnames, patronymics, emails, general emails, phones, addresses, job titles

    Russian language support – Utilizes Natasha, spaCy, and pymorphy2 for robust Russian NLP

    Interactive UI – Built with ipywidgets, designed for Google Colab

    Flexible input – Upload any Excel file and select the column containing company names

    Merge option – Combine extracted data with another Excel file

    Email campaign enrichment – Match email addresses against delivery reports to append send status and timestamps

    Simple file concatenation – Additional utility to glue two Excel files together

    One‑click download – Processed files are automatically downloaded

🧰 Tech Stack

    Python 3, pandas, openpyxl

    Natasha – NER, address extraction, names

    spaCy (ru_core_news_sm) – LOC entity recognition

    pymorphy2 – lemmatization for position matching

    ipywidgets, IPython – interactive interface for Colab

📦 Installation & Usage

The notebook is self‑contained – the first cell installs all required dependencies.
Run cells sequentially, upload your Excel file, choose the relevant column, and click Извлечь.
For email enrichment, load your base file and the report file, then click Проверить совпадения.
