# Python Development Tools Configuration

## Project Descriptors

`pyproject.toml` replaces `setup.py`. It can be used together with the standard `setup.cfg`

## Formatting

Formatting and linting are configured by the `.flake8` file. It is recommended to use flake8 and autopep8

For VSCode add to the settings:

```json
"settings": {
    "python.linting.enabled": true,
    "python.linting.flake8Enabled": true,
    "python.linting.flake8Args": ["--config=.flake8"],
    "python.formatting.provider": "autopep8",
    "python.formatting.autopep8Args": [ "--global-config=.flake8"],
}
```
