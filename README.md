# Charmaine Boitumelo Putu — Flask Portfolio

A modern, responsive personal portfolio built with Python and Flask. It presents the home introduction, requested About Me statement, technical and soft skills, education, certifications, Python projects, contact details and downloadable resume.

## Run locally

```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\\Scripts\\activate
pip install -r requirements.txt
python app.py
```

Open `http://127.0.0.1:5000` in your browser.

The existing PDF certificates, resume and `.py` projects remain in the repository and are linked directly from the Flask template. GitHub Pages cannot execute a Flask server directly; deploy this Python app to a Python-capable host such as Render, Railway or PythonAnywhere. For GitHub Pages hosting, the same template can be exported to static HTML.
