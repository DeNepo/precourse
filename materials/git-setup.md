# Git Setup

> More details (starting at step 2.2)
> [odin project](https://www.theodinproject.com/lessons/foundations-setting-up-git#step-2-configure-git-and-github)

Add `user name` to git

```Markdown
  git config --global user.name "your gitHub user name"
```

Add `email` to git

```Markdown
  git config --global user.email "your email"
```

Set your default branch reconciliation behavior for merging.

```Markdown
  git config --global pull.rebase false
```

Make `VS code` the default editor

```Markdown
git config --global core.editor "code --wait"
```

Handle the end line <br> Mac or Linux

```Markdown
git config --global core.autocrlf input
```

Windows

```Markdown
git config --global core.autocrlf true
```

See all git global configuration in your `VS code`

```Markdown
git config --global -e
```

Initialize empty git repo

```Markdown
git init
```

List all the untracked files

```Markdown
git status
```

Add file(s) to staging area

```Markdown
git add <file name>
```

Add all file(s) to staging area

```Markdown
git add .
```

Remove file(s) from staging area

```Markdown
git reset <file name>
```

Commit changes

```Markdown
git commit -m " descriptive message"
```

Save changes without committing them temperately

```Markdown
git stash
```

To restore or reapply the stashed changes

```Markdown
git stash apply
```

To create a new branch

```Markdown
git branch <branch name>
```

To switch to the new branch

```Markdown
git checkout <branch name>
```

To create a new branch and switch to it

```Markdown
git checkout -b <branch name>
```

To revert a commit

```Markdown
git revert <A commit hash>
```

To reset the changes

```Markdown
git reset
```

To display the most recent commits

```Markdown
git log
```

To compare changes

```Markdown
git diff
```

To integrate changes from one branch onto another

```Markdown
git rebase <branch name>
```
