# Branch Recovery Notes

When a branch gets into an unexpected state:

1. Inspect `git status` and recent history.
2. Identify the last known-good commit.
3. Preserve uncommitted work before resetting or switching branches.
4. Prefer revert for shared history when appropriate.
5. Verify the resulting branch and working tree.

Understand the effect of a Git command before running destructive operations.
