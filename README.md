# Probiwinz.github.io

Simple static page about Beluga whales.

## HTML Linting

This repository uses [HTMLHint](https://htmlhint.com/) to lint `index.html`.

To run the linter locally, install Node.js and run:

```bash
npm install -g htmlhint  # or use npx htmlhint
htmlhint index.html
```

The included GitHub Actions workflow automatically runs the same check on every push or pull request to the `master` branch.
