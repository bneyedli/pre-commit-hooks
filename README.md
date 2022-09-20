pre-commit-hooks
================

Custom hooks for pre-commit

See also: https://github.com/pre-commit/pre-commit


### Usage

Append to `.pre-commit-config.yaml`

```yaml
-   repo: https://github.com/bneyedli/pre-commit-hooks
    rev: main
    hooks:
    - id: python-bandit
    - id: python-black
    - id: python-flake8
    - id: python-isort
    - id: python-mypy
    - id: python-pylint
    - id: python-pytype
    - id: python-semgrep
```
