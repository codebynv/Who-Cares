# Git Practice Commands

## Inspect

```bash
git status
git log --oneline --decorate -5
git diff
```

## Branch

```bash
git switch -c docs/my-change
git switch main
```

## Commit

```bash
git add .
git commit -m "docs: describe change"
git push -u origin docs/my-change
```

## Review before pushing

Check the diff and status first. A commit should contain only the files and changes that belong to its stated purpose.
