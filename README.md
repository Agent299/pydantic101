# pydantic101

## Continuous integration

GitHub Actions runs on pushes and pull requests targeting `main`. The workflow
uses the Python version in `.python-version`, installs dependencies from
`uv.lock`, checks Python syntax, and runs the `pydantic101` CLI smoke test.