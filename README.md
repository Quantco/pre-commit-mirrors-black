# black pre-commit hook

pre-commit hook of black with conda as a `language` / package manager.

For pre-commit: see [here](https://github.com/pre-commit/pre-commit)

For black: see [here](https://github.com/psf/black)

## Using black with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/quantco/pre-commit-mirrors-black
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: black-conda
```
