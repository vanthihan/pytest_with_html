# pytest_with_html
Sample pytest with html report

# Install pytest and pytest-html
pip install pytest pytest
pip install pytest pytest-html

# reate venv
python -m venv myvenv

# Active venv
.\myvenv\Scripts\activate


# gen report with contained html

pytest --html=report.html --self-contained-html