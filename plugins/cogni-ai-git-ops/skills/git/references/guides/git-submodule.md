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
