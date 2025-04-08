# GIT 🐈‍⬛

Here are some important commands related to Git !

---

```bash
$ git --version
```

Verify the Git version installed.

```bash
$ git config --global user.name "Your Name"
```

Defines your name.

```bash
$ git config --global user.email "your@email.com"
```

Defines your e-mail.

```bash
$ git config --list
```

Show current configs.

```bash
$ git init
```

Initializes a new Git repository in the current directory.

```bash
$ git branch
```

List all local branches (-a for all branches, including remote).

```bash
$ git branch <branch-name>
```

Creates a new branch.

```bash
$ git checkout <branch-name>
```

Switches to the specified branch.

```bash
git merge <branch-name>
```

Merges changes from <branch-name> into the current branch.

```bash
$ git rebase <branch-name>
```

Reapplies commits from the current branch onto another branch (rewrites history).

```bash
$ git restore <file>
```

Discards unstaged changes in life.

```bash
$ git reset --hard HEAD
```

Resets the working directory to the last commit (caution: deletes uncommited changes).

```bash
$ git revert <commit-hash>
```

Creates a new commit that undoes a previous commit (safe for shared history).

```bash
$ git stash
```

Temporalily saves uncommitted changes for later use.

```bash
$ git stash pop
```

Restores the most recently stashed changes.

```bash
$ git add .
```

Stages changes for commit.

```bash
$ git push
```

Uploads local commits to the remote repository.

```bash
$ git pull
```

Fetches changes from the remote repository and merges them into the local branch.

```bash
$ git fetch
```

Downloads changes from the remote but does not merge them.

```bash
$ git clone <repository-url>
```

Clones (downloads) a remote repository to your local machine.

```bash
$ git status
```

Shows the current state of the working directory.

```bash
$ git commit -m "Commit Message"
```

Commit command.

```bash
$ git branch -M main
```

Rename the current branch to "main".

```bash
$ git remote add origin REPOSITORY_URL
```

Link your local Git repository to a remote repository.

```bash
$ git push -u origin main
```

Send commits to remote repository. The flag -u links the local branch to the remote one. Origin is the alias that references Github URL.

```bash
$ git remote -v
```

Lists all connected remote repositories.

```bash
$ git remote add <name> <url>
```

Adds a new remote repository.

```bash
$ git push -u origin <branch>
```

Pushes a local branch to a remote repository and sets upstream tracking.

```bash
$ git log
```

Displays the commit history.

```bash
$ git log --oneline --graph
```

Shows a compact commit history with branch visualization.

```bash
$ git diff
```

Shows unstaged changes (differences between working directory and last commit).

```bash
$ git blame <file>
```

Shows who last modified each line in a file.
