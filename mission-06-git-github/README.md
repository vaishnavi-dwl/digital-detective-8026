## Task 6.1: Basic Git workflow

| Git operation | What it does in my own words |
|---|---|
| Check repository status: `git status` | Shows which files have been changed, staged, or are not being tracked by Git. |
| Stage selected changes: `git add README.md` | Selects the README changes to include in the next commit. |
| Create a commit: `git commit` | Saves a snapshot of the staged changes in the repository with a message. |
| View commit history: `git log --oneline` | Displays previous commits and their short descriptions. |

**Staging vs committing:**
- Staging (`git add`) means choosing which changes should go into the next saved version.
- Committing (`git commit`) means saving those staged changes as a recorded version in Git. A commit is stored in the local repository and is not automatically uploaded to GitHub.

## Task 6.2: Branch and README update

| Git command / operation | One-line explanation |
|---|---|
| `git init` | Creates a new Git repository in the current folder. |
| `git status` | Shows the current state of files and changes in the repository. |
| `git add filename` | Stages a selected file so its changes can be included in the next commit. |
| `git commit -m "message"` | Saves staged changes as a new version with a descriptive message. |
| `git log --oneline` | Shows the repository's commit history in a short format. |
| `git branch` | Lists the branches in the repository. |
| `git branch branch-name` | Creates a new branch without switching to it. |
| `git switch branch-name` | Switches to an existing branch. |
| `git switch -c branch-name` | Creates a new branch and switches to it. |
| `git push` | Publishes local commits to the connected remote repository. |
| `git pull` | Retrieves and integrates the latest changes from the remote branch. |
