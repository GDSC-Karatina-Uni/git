# git

## Terms

### Repository

A repository is a storage space where your project lives. It can be local to a folder on your computer, or it can be a storage space on GitHub or another online host. You can keep code files, text files, image files, you name it, inside a repository.

### Working Directory

The Working Directory is the files that you see in your computer's file system. When you open your project files up on a code editor, you're working with files in the Working Directory.

### Staging Area

The Staging Area is a file, generally contained in your Git directory, that stores information about what will go into your next commit. It's sometimes referred to as the "Index", but it's best to avoid this term, as it can be confused with "the index", which is a pointer to a commit. The Staging Area will contain any files that you've added to your Git repository by using git add. If you make a change to a file, it will be modified in your Working Directory. To update it in the Staging Area, you must add the file again using git add.

## Commands

```bash
git init
```

This command is used to start a new repository.

```bash

git clone <repo>
```

This command is used to obtain a repository from an existing URL.

```bash
git add <file>
```

This command adds a file to the staging area.

```
git add *
```

This command adds all files in the current directory to the staging area.

```bash
git commit -m "Commit message"
```

This command records or snapshots the file permanently in the version history.

```bash
git status
```

This command lists all the files that have to be committed.

```bash
git log
```

- Sample Output

    ![git log](/images/log.png)

- HEAD points to the last commit in the branch.

This command is used to list the version history for the current branch.

```bash
git push
```

This command sends the committed changes of master branch to your remote repository.

```bash
git pull
```

This command fetches and merges changes on the remote server to your working directory.

```bash
git branch
```

This command lists all the local branches in the current repository.

```bash
git checkout <branch>
```

This command is used to switch from one branch to another.

```bash
git checkout
```

```bash
git diff
```

This command shows the file differences which are not yet staged.

```bash
git checkout <file>
```

This command unstages the file, but it preserves the file contents.

