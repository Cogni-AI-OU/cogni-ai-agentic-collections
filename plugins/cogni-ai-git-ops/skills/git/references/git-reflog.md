# Reflog Recovery (`git reflog`)

- **Objective**: Recover lost commits, branches, or undo a destructive operation (like a bad hard reset).
- **Process**:
  - View history of HEAD movements: `git reflog`
  - Identify the target commit SHA (e.g., `HEAD@{2}`).
  - Restore state: `git reset --hard <sha>` or create a branch: `git branch <branch-name> <sha>`.