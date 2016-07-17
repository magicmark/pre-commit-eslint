# pre-commit ESLint Hook

This is a hook to allow [pre-commit](http://pre-commit.com) to interface with a local [eslint](http://eslint.org) configuration.

### Installing

Ensure you have eslint installed locally via your package.json.

Add this to your `.pre-commit-config.yaml`:

```
-   repo: git://github.com:magicmark/pre-commit-eslint
    sha: '' # Use the sha you want to point at
    hooks:
    -   id: local-eslint
```
