# Weather 

> Proyecto final — Big Data · Grado en Matemáticas · UNIE Universidad

[![CI](https://github.com/alvarodiez20/weather/actions/workflows/ci.yml/badge.svg)](https://github.com/alvarodiez20/weather/actions/workflows/ci.yml)
[![Docs](https://github.com/alvarodiez20/weather/actions/workflows/docs.yml/badge.svg)](https://alvarodiez20.github.io/weather/)
[![Coverage](https://codecov.io/gh/alvarodiez20/weather/graph/badge.svg)](https://codecov.io/gh/alvarodiez20/weather)
[![Python](https://img.shields.io/badge/python-3.10%2B-blue)](https://www.python.org/)
[![Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json)](https://github.com/astral-sh/ruff)

---

## Description

*(Replace with your line-of-work description.)*

## Documentation

Full documentation at **[alvarodiez20.github.io/weather](https://alvarodiez20.github.io/weather/)**

## Installation

  ```bash
  git clone https://github.com/USER/proyecto-meteorologia.git
  cd proyecto-meteorologia
  pip install uv
  uv sync --group dev
  ```

## Data Download

Data is not included in the repository. To download:

  ```bash
  # TODO: add your data download instructions
  ```

## Usage

  ```bash
  uv run pytest                          # run tests
  uv run pytest --cov=src -v     # tests with coverage
  uv run ruff check .                    # lint
  uv run ruff format .                   # format
  uv run mkdocs serve                    # preview docs at localhost:8000
  ```

## Project Structure

  ```
  proyecto-meteorologia/
  ├── .github/workflows/   # CI/CD pipelines
  ├── data/                # Data files (not committed — see .gitignore)
  ├── docs/                # MkDocs documentation sources
  ├── notebooks/           # Exploratory notebooks
  ├── src/weather/         # Source package
  ├── tests/               # Unit and integration tests
  ├── mkdocs.yml
  ├── pyproject.toml
  └── README.md
  ```

## Author

**Your Name** · [github.com/USER](https://github.com/USER)

## Professor
**Álvaro Diez** · [github.com/alvarodiez20](https://github.com/alvarodiez20)

---

*Big Data · 4º Grado en Matemáticas · UNIE Universidad · 2025–2026*