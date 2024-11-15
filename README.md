# My Python Project using pyproject.toml

This project showcases a typical Python project structure using `pyproject.toml`, demonstrating good practices for organizing code, dependencies, and tests.


## Installation

To build:

```sh
pip install .
```
Or for editable installation:
```sh
pip install -e .
```

For development:
```sh
poetry install --with dev 
```

# Usage
To run the main script:
```sh
python -m src
```

# Project Structure
```
.
├── pyproject.toml
├── poetry.lock
├── README.md
├── src/
│   ├── __main__.py # or just main.py/app.py
│   ├── myturtle/
│   │   ├── __init__.py
│   │   └── myturtle.py
│   └── snake/
│       ├── __init__.py
│       └── snake.py
├── tests/
└── venv/
```
# License
This project is licensed under the MIT License.