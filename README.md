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

## Related projects

- [actdocs](https://github.com/tmknom/actdocs): Generate documentation from Actions and Reusable Workflows.
- [template-composite-action](https://github.com/tmknom/template-composite-action): Template repository for Composite Action.
- [template-reusable-workflows](https://github.com/tmknom/template-reusable-workflows): Template repository for Reusable Workflows.

## Release notes

See [GitHub Releases][releases].

[releases]: https://github.com/tmknom/docs-workflows/releases
