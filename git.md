# GIT 🐈‍⬛

Here are some important commands related to Git !

---

```bash
$ git --version
```

Verify the Git version installed.

```bash
$ git config --global user.name "Seu Nome"
```

Defines your name.

```bash
$ git config --global user.email "seu@email.com"
```

Defines your e-mail.

```bash
$ git config --list
```

Show current configs.

```bash
$ git init
```

Inits a local repository.

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

Verify the linked remote repository URL.
