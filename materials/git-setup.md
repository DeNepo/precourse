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
