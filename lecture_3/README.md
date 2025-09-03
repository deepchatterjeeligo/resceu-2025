# Environment

Dependency requirements are specified in `requirements.txt`. You can use
[uv](https://docs.astral.sh/uv/getting-started/installation/) to install dependencies
in the same way as the previous lecture.
```bash
$ uv venv --python=3.11 && uv pip install -r requirements.txt
```
Start the `jupyter-notebook` using the `uv` entrypoint:
```bash
$ uv run jupyter-notebook
```
