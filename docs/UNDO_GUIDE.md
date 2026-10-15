# Undoing Git Changes Safely

Choose the undo operation based on where the change exists.

- Unstaged changes: inspect before using restore.
- Staged changes: unstage before deciding whether to discard.
- Local commits not shared: consider reset only when its effect is understood.
- Shared commits: prefer a revert when preserving history matters.

Check status and inspect the diff before and after the operation. Back up work before destructive commands.
