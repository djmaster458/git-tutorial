# Useful Commands
## Getting Around
`git status`
- Displays information about the working branch/commit
  - Current branch
  - Is it synchronized with the tracked remote branch?
  - Changes staged for commit
  - Changes not staged for commit and untracked files

`git checkout <branch/commit>`
`git switch <branch/commit>`
- Changes your workspace to the target branch or commit
- If a commit is selected, it will be in a `Detached` state from the history (useful for submodules)

## Cleaning up
`git reset –-hard`
- Resets all files to their committed version

`git clean -fd`
- Deletes all files that aren't part of version control (files you added that aren't checked in anywhere)

`git checkout <branch/commit> -- path/to/file`
- Resets path/to/file to the version of the commit that you currently have checked out
- Brings in file from that branch/commit if not already present
