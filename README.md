# Format a renovate change

Re-formats a Python codebase after a relevant renovate change.

## Example Usage

```
  format-renovate-change:
    runs-on: ubuntu-latest
    permissions:
      contents: write
    steps:
      - uses: infrabits/ci-format-renovate-change@main
        with:
          github_token: ${{ github.token }}
```
