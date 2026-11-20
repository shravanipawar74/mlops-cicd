# MLOps CI/CD Pipeline with GitHub Actions

A simple machine learning project using Logistic Regression
on the Iris dataset with an automated CI/CD pipeline.

## Pipeline Overview

Code Commit -> Build -> Test -> Deploy

## Technologies Used

- Python
- Scikit-learn
- Pytest
- GitHub Actions

## Project Structure

- src/model.py - ML model training
- tests/test_model.py - Unit testing
- requirements.txt - Dependencies
- app.py - Application file
- .github/workflows/ci-cd.yml - CI/CD configuration

## Run Locally

```bash
pip install -r requirements.txt
python src/model.py
pytest -v
```

## CI/CD Process

The test job checks the ML application.
If all tests pass on the main branch,
the deployment job is executed.
