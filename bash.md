# BASH 🐧

Here are some important commands avaliable in Bash !

---

```bash
pwd
```

Shows the current directory path. (Print Working Directory)

```bash
ls
```

List files/folders in the current directory. (List Directory Contents)

```bash
ls -l
```

Detailed list.

```bash
ls -a
```

Show hidden files.

```bash
cd [directory]
```

Change working directory.

```bash
mkdir [name]
```

Make directory. Creates a new folder.

```bash
rm [file]
```

Deletes a file

```bash
rm -f [file]
```

Force - ignore nonexistent files and never prompt.

```bash
rm -i [file]
```

Interactive - ask before each file is deleted.

```bash
rm (-r OR -R) folder/
```

Recursive - remove directories and their contents.

```bash
rm -rf folder/
```

Recursive + Force - delete everything without asking.

```bash
rm -v file.txt
```

Verbose - show what is being removed.

```bash
cp [source] [destination]
```

Copies files/folders.

```bash
mv [source] [destination]
```

Moves files or renames them.

```bash
touch [file]
```

Creates an empty file or updates its timestamp.

```bash
cat [file]
```

Displays file content.

```bash
cat file1.txt file2.txt > file3.txt
```

Concatenates files content and creates a new file.

```bash
less [file]
```

View file page-by-page (press q to quit).

```bash
nano [file]
```

Opens a simple text editor.

```bash
grep "pattern" [file]
```

Global Regular Expression Print - Searches for text patterns in files.

```bash
sudo [command]
```

SuperUser DO - Runs a command with admin privileges.

```bash
top
```

Displays running processes and resource usage (like Task Manager).

```bash
ps
```

Process Status - Shows active processes.

```bash
kill [PID]
```

Terminates a process by its ID.

```bash
df -h
```

Disk Free - Shows disk space usage.

```bash
free -h
```

Displays RAM usage.

```bash
ping [host]
```

Tests network connectivity to a server.

```bash
curl [URL]
```

Transfers data from/to a server (e.g., download files).

```bash
wget [URL]
```

Downloads files from the web.

```bash
ssh [user@host]
```

Secure Shell - Connects to a remote server.

```bash
apt update
```

Updates the package list.

```bash
apt install [package]
```

Installs a software package.

```bash
apt remove [package]
```

Uninstalls a package.

```bash
chmod [permissions] [file]
```

Change Mode - Modifies file permissions.

```bash
chown [user];[group] [file]
```

Change Owner - Changes file ownership.

```bash
echo "something"
```

Prints something to the terminal.

```bash
history
```

Show your command history.
