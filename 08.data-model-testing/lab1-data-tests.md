---
duration: 2h
---

# Testing

Now we know how to version the data, the models, the environment, and how link it to the source code. But we don't know if the data is of good quality and if the code behaves as it should. Let's write some tests!

**Objectives:**

- Learn how to define a test function and how to write an assertion.
- Learn the approach to data testing.
- Learn the approach to feature engineering testing.

**Dependencies:**

- Notebooks:
  - Exercises (start with this one): `testing_initial.ipynb`
- Dataset: `winequality-red.csv`
- Install: `pip install -U pytest`, `pip install ydata-profiling` (if it doesn't work, try `conda install -c conda-forge ydata-profiling`), `pip install ipywidgets`, `pip install ipytest` (the last one enables you to run pytest in a notebook), `pip install notebook`

**Instructions:**

1. Activate your virtual environment (`env_mlops`)
2. Install the dependencies
3. Download the notebook and the dataset
4. Start Jupyter Notebook: `jupyter notebook`
5. Follow the notebook with the following exercises:
  - `ydata-profiling`:
    - Generate the reports about the datasets
    - Explore them to see how they can help you getting the insights about the data
    - How could you combine them with DVC and Git (data versioning)?
  - Testing with `pytest`:
    - Test the functions (refresher)
    - Test the datasets
    - Test engineered features
