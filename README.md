# docs-workflows

Collection of docs workflows.

## Description

A collection of docs workflows implemented as Reusable Workflows for GitHub Actions.

## Usage

### Composite Action

```yaml
jobs:
  call:
    uses: tmknom/docs-workflows/.github/workflows/composite-action.yml@v0
    permissions:
      contents: write
      pull-requests: write
```

## Release notes

See [GitHub Releases][releases].

## License

Apache 2 Licensed. See [LICENSE](LICENSE) for full details.

[releases]: https://github.com/tmknom/docs-workflows/releases
