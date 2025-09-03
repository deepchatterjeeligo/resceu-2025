# Environment

Dependency requirements are specified in `requirements.txt`. You can use
[uv](https://docs.astral.sh/uv/getting-started/installation/) to install dependencies
in the same way as the previous lecture.
```bash
$ uv venv --python=3.11 && uv pip install -r requirements.txt
```

# Notebooks
There are two notebooks. The first demonstrates the approximation of a bi-modal distribution using a normalizing flow. The second demonstrates performing posterior estimation on the slope and intercept of a linear model using simulation-based inference.
