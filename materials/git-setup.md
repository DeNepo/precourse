# Git Setup

- Add `user name` to Git

```Markdown
  git config --global user.name "your GitHub user name"
```

- Add `email` to Git

```Markdown
  git config --global user.email "your email"
```

- Set your default branch reconciliation behavior for merging.

```Markdown
  git config --global pull.rebase false
```

- Make `VS Code` the default editor

```Markdown
git config --global core.editor "code --wait"
```

- Handle the end line <br> Mac or Linux

```Markdown
git config --global core.autocrlf input
```

Windows

```Markdown
git config --global core.autocrlf true
```

- See all Git global configuration in your `VS Code`

```Markdown
git config --global -e
```

- [MORE INFO](https://www.theodinproject.com/lessons/foundations-setting-up-git#step-2-configure-git-and-github)
