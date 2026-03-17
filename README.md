# nb2pdf_agent: Professional Notebook Reporter

An AI-powered conversion tool that transforms Jupyter Notebooks (.ipynb) into polished, ready-to-submit PDF lab reports.

## 🛠️ Requirements
This agent requires **wkhtmltopdf** to be installed on your system to handle the HTML-to-PDF conversion.

1. **System Tool:** [Download wkhtmltopdf](https://wkhtmltopdf.org/downloads.html) and install it.
2. **Python Libraries:**
   ```bash
   pip install nbformat markdown2 pdfkit pygments jinja2
   ## 🛠️ Installation

###  Quick Install (Standard)
```bash
pip install -r requirements.txt
## ⚡ Fast Installation (using uv)
If you have [uv](https://github.com/astral-sh/uv) installed, you can run the agent without even installing dependencies manually:

```bash
uv run nb2pdf DS_notebook.ipynb