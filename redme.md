
## Directory Descriptions

### `data/`
- **`Orignal/`**: Store Orignal data and images
- **`processed/`**: Store cleaned and processed data files ready for tranig.
- **`external/`**: Store data from external sources (e.g., APIs, third-party datasets).

### `notebooks/`
- Contains Jupyter notebooks for exploratory and experimentation.

### `src/`
- **`__init__.py`**: Makes the `src` directory a Python package.
- **`data_processing.py`**: Scripts for cleaning, transforming, and preprocessing data.
- **`models/`**: Contains code for training, evaluating, and saving machine learning models.

### `tests/`
- Contains unit tests and test cases to ensure the reliability of the code.

### `requirements.txt`
- Lists all Python dependencies required for the project. Install them using:
  ```bash
  pip install -r requirements.txt