name: Simple CI Python Application

on:
  push:
    branches: [ "main" ]

jobs:
  dev:
    runs-on: ubuntu-latest

    steps:
      - name: Checkout code
        uses: actions/checkout@v4

      - name: Set up Python
        uses: actions/setup-python@v5
        with:
          python-version: "3.11"

      - name: Run Python app
        run: python app.py
