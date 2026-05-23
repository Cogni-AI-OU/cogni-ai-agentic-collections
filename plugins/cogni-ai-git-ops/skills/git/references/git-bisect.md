# Bisecting (`git bisect`)

- **Objective**: Use binary search to find the exact commit that introduced a bug.
- **Process**:
  - Start: `git bisect start`
  - Mark broken commit (usually current): `git bisect bad`
  - Mark known good commit: `git bisect good <good-commit-sha>`
  - Git will checkout intermediate commits. Test, then mark `git bisect good` or `git bisect bad`.
  - Conclude: `git bisect reset` to return to the original branch.
