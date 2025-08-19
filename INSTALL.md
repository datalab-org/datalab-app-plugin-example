# Installation

We recommend you use [`uv`](https://astral.sh/uv) for managing virtual environments and Python versions.

Once you have `uv` installed, you can clone this repository and install the package in a fresh virtual environment with:

```
git clone git@github.com:datalab-org/datalab_app_plugin_example
cd datalab_app_plugin_example
uv sync --all-extras --dev
```

## Development installation

You can activate `pre-commit` in your local repository with `uv run pre-commit install`.
This will call `pre-commit` automatically on every commit to check for code style and other issues, and will also be used in the CI.
