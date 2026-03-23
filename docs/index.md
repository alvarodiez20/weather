# Weather

Proyecto final — Big Data · Grado en Matemáticas · UNIE Universidad

## Descripción

Análisis de datos meteorológicos utilizando Python.

## Instalación

```bash
git clone https://github.com/alvarodiez20/weather.git
cd weather
pip install uv
uv sync --group dev
```

## Uso

```bash
uv run pytest                      # ejecutar tests
uv run pytest --cov=src -v         # tests con cobertura
uv run ruff check .                # lint
uv run ruff format .               # formato
uv run mkdocs serve                # preview docs en localhost:8000
```
