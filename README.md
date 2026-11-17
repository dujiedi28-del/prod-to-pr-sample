# Sample Repo (Practice Project)

This is a small practice project with a tiny bug, used to test the **Prod-to-PR** helper.

## What’s inside
- `calculator.py` — simple math functions (one has a bug)
- `test_calculator.py` — tests that check the functions (one test fails because of the bug)
- `requirements.txt` — what’s needed to run the tests (`pytest`)

## Run tests locally
```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
pytest -q
```

You should see **1 failing test**. The goal is for the Prod-to-PR helper to propose a fix.
