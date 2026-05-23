# Advanced Cherry-Picking

- **Objective**: Apply specific commits from one branch to another without merging the whole branch.
- **Process**: `git cherry-pick <commit-sha>`
- **Multiple commits**: `git cherry-pick <sha-A>^..<sha-B>`
- **No commit (stage only)**: `git cherry-pick -n <commit-sha>`
