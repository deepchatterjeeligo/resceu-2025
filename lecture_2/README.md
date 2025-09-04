# Install dependencies

Dependency requirements are specified in `requirements.txt`. You can use
[uv](https://docs.astral.sh/uv/getting-started/installation/) to install dependencies.
This installation **does not** require a virtual environment.

Under the `lecture_2` directory, run the following to create a virtualenv and install dependencies.
```bash
$ uv venv --python=3.11 && uv pip install -r requirements.txt
```
This will create a `.venv` under the `lecture_2` directory, which you can then activate using
```bash
$ source .venv/bin/activate
```
When running the notebook, use the interpreter in `lecture_2/.venv/bin/python`.
