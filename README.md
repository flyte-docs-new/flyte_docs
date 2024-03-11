# New Flyte docs

To build and view these docs locally:

1. Create and activate a new virtual environment:
```
python -m venv .venv; source .venv/bin/activate
```
2. Install `pip-tools`:
```
python -m pip install pip-tools
```
3. Compile requirements:
```
pip-compile requirements.in
```
4. Install requirements:
```
pip install -r requirements.txt
```
5. Build docs:
```
sphinx-build -M html docs/_src docs/_build
```
6. View docs:
```
open docs/_build/html/index.html
```
