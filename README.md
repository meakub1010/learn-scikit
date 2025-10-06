### Learn scikit-learn

**create virtual environment**

```ps
python -m venv sklearn-env
source sklearn-env/bin/activate  # activate
pip install -U scikit-learn
```

```ps
python -m pip show scikit-learn  # show scikit-learn version and location
python -m pip freeze             # show all installed packages in the environment
python -c "import sklearn; sklearn.show_versions()"
```