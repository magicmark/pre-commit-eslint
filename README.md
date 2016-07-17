# pre-commit ESLint Hook

This is a hook to allow [pre-commit](http://pre-commit.com) to interface with a local [eslint](http://eslint.org) configuration.

### Installing

Ensure you have eslint installed locally via your package.json.

Add this to your `.pre-commit-config.yaml`:

```
-   repo: git://github.com:magicmark/pre-commit-eslint
    sha: 797aeef96c9ba5aa26450a9a1fc3f7f5a8730647
    hooks:
    -   id: local-eslint
```
