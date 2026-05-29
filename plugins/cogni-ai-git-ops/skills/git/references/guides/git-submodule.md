# Git Submodule Management Reference

## Critical Safety Rules

- **NEVER** remove the `.gitmodules` file before deinitializing submodules.
- Submodule reference directories MUST be removed via `git rm` before removing configuration sections.
- Only remove the `.gitmodules` file itself when it is empty, cannot be deinitialized, or is completely broken.

## Safe Removal Protocol

To properly remove or cleanup a submodule:

1. **Remove the Submodule Directory:**
   ```bash
   git rm <path_to_submodule>
   ```

2. **Deinitialize the Submodule:**
   ```bash
   git submodule deinit -f -- <path_to_submodule>
   ```

3. **Remove Configuration Sections:**
   Use the following command to remove sections from `.gitmodules` or `.git/config`:
   ```bash
   git config --file .gitmodules --remove-section submodule.<name>
   git config --remove-section submodule.<name>
   ```

4. **Cleanup Git Internals:** (only if exist)
   ```bash
   rm -v .git/modules/<name>
   ```

## References

To fully utilize this guide, you SHOULD read the links relevant to the current context:

- [Git Recovery & Troubleshooting](recovery.md)
  Reference MUST be loaded when performing repository recovery, solving complex conflicts, or manipulating history.
- [Reflog Recovery (git reflog)](git-reflog.md)
  Reference MUST be loaded when using `git reflog` to recover lost commits, branches, or undo destructive operations.
- [Git Merge](git-merge.md)
  Reference MUST be loaded before performing a git merge, ensuring no conflict markers or duplicate lines are present.
- [Git Rebase](git-rebase.md)
  Reference MUST be loaded before performing Git rebase operations (interactive history cleanup or non-interactive rewrites).
- [Git Skill](../../SKILL.md)
  Usage for basic Git operations and repository management. This is the core skill for all git interactions.


