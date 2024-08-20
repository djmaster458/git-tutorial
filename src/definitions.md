# Definitions
## Git
### Commit
A commit is a snapshot of your repository at a specific point in time.
It represents a set of changes that have been made to the files in the repository.
Each commit has a unique identifier (hash) and includes metadata such as the author, date, and a commit message describing the changes.

### Branch
A branch represents a timeline of commits.
Under the hood, a branch is just a pointer to a series commits.
They allow for parallel development to avoid interfering directly with co-developers or stable code states.

### Merge
A merge is one branch attempts to join into another, merging their timelines.
Usually there is a source branch and incoming branch.
The incoming branch's changes will be merged into the source branch through a new commit that will be added to the source branch.

Depending on the files changes and timings, Git will either automatically handle merging each file, or may require manual intervention to resolve the merge conflicts.

## GitHub
### Pull Request
A pull request is a feature of GitHub that allows your feature branch to be reviewed before merging into another branch.
This allows for developers to review each others' code for bugs or missing specifications.

### ZenHub Extension
We use this for agile
