# actions

GitHub actions I use for CI.

## Useful commands

```bash
# Create PRs
gh pr create --title $TITLE --head $BRANCH

# Create GitHub releases
gh release create --verify-tag --generate-notes $TAG

# Upstream sync
gh repo sync --branch $BRANCH
```
