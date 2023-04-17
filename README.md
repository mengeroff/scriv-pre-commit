# scriv-pre-commit

A [pre-commit](https://pre-commit.com/) hook for [Scriv](https://github.com/nedbat/scriv).

Distributed as a standalone repository to enable installing Scriv via prebuilt wheels from
[PyPI](https://pypi.org/project/scriv/).

### Using Scriv with pre-commit

Add this to your `.pre-commit-config.yaml`:

```yaml
- repo: https://github.com/mengeroff/scriv-pre-commit
  # Scriv version.
  rev: '1.3.1'
  hooks:
    - id: scriv
```

## License

MIT
