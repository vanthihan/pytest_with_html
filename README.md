# pytest_with_html
Sample pytest with html report

Install pytest and pytest-html
``` bash
pip install pytest pytest
pip install pytest pytest-html
```
Create venv
``` bash
python -m venv myvenv
```
Active venv

``` bash
.\myvenv\Scripts\activate
```

gen report with contained html

``` bash
pytest --html=report.html --self-contained-html
```
