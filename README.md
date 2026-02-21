# TY pre-commit

For TY: see https://github.com/astral-sh/ty

For pre-commit: see https://github.com/pre-commit/pre-commit

## Using TY with pre-commit

Add this to your `.pre-commit-config.yaml`:

```yaml
- repo: https://github.com/hoxbro/ty-pre-commit
  rev: v0.0.18
  hooks:
    - id: ty-check
```
