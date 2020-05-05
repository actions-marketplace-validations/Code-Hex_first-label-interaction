# First Label Interaction

![Test Issue Label](https://github.com/Code-Hex/first-label-interaction/workflows/Test%20Issue%20Label/badge.svg)

An action for labeling pull requests or issues from first-time contributors.

Most of the code is refered to https://github.com/actions/first-interaction.

# Usage

See [action.yml](action.yml)

```yaml
steps:
- uses: Code-Hex/first-label-interaction@v1.0.1
  with:
    repo-token: ${{ secrets.GITHUB_TOKEN }}
    issue-labels: '["good first issue", "help wanted"]'
    pr-labels: '["help wanted"]'
```

# License

The scripts and documentation in this project are released under the [MIT License](LICENSE)
