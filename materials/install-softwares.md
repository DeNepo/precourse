# Install Softwares

Before getting to work you will need to make sure your computer is ready to go.
In the _Software Installations_ and _VSCode Extensions_ sections of your
`precourse` issue is a list of the softwares you will need to succeed at HYF.

- [ ] [Slack](https://slack.com/) -
      [Slack Windows](https://slack.com/downloads/windows) -
      [Slack Mac](https://slack.com/downloads/mac) -
      [Slack Linux](https://slack.com/downloads/linux) -
      [Slack Android](https://play.google.com/store/apps/details?id=com.Slack&hl=en&gl=US) -
      [Slack iOS](https://apps.apple.com/us/app/slack/id618783545) - for all HYF
      communication
- [ ] [Discord](https://discord.com/download) - for all HYF communication
- [ ] [Zoom](https://zoom.us/support/download) - for online class
- [ ] Modern Browsers with good DevTools, it's good to practice with all of
      them:
  - [Chromium](https://download-chromium.appspot.com/), and/or
    [Chrome](https://www.google.com/chrome/)
  - [Firefox](https://www.mozilla.org/en-US/firefox/developer/)
  - [Edge](https://www.microsoft.com/en-us/edge)
  - [Responsively](https://responsively.app/) - a browser with extra features
    for developing responsive and accessible user interfaces
  - [Replay](https://www.replay.io/) - record your web pages as you use them and
    share your recordings to collaboratively study or debug. Super helpful when
    you start learning JavaScript!
- [ ] [Visual Studio Code](https://code.visualstudio.com/download) - used write
      and edit your code
- GitHub Desktop (optional)
  - This can help you get started with Git & GitHub, but does not replace
    learning to use your CLI
  - [Mac](https://desktop.github.com/)
  - [Linux](https://github.com/shiftkey/desktop#debianubuntu-distributions)
- If you use Windows:
  - [setup a Linux SubSystem](https://docs.microsoft.com/en-us/windows/wsl/install-win10)
- You will need to update to Windows 10:
  [itechguides](https://www.itechguides.com/windows-subsystem-for-linux/),
  [adamtheauthor](https://adamtheautomator.com/windows-subsystem-for-linux/)
  - [Learn to open VSCode with your SubSystem](https://docs.microsoft.com/en-us/windows/wsl/tutorials/wsl-vscode)

## Git

### Git On Mac

1. Press `command` and `space` and type `terminal` then click `enter`
2. In the `terminal` type `git --version` if you got a version then you already
   have git.
3. If you didn't get a version then you need to install `Homebrew`
4. Paste this in your terminal and click `enter`

   ```markdown
   /bin/bash -c "$(curl -fsSL
   https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```

5. After you installed `Homebrew` , use the command `brew install git` to
   install git.

### Git on Windows

1. Click on the `search` icon and type `cmd`.
2. Type `git --version` if you got a version then you already have `git`
3. If not [install git for Windows](https://gitforwindows.org/)

### Git on Linux

1. It depends on your distribution, if you are using `Ubuntu`
2. Open your terminal and type `git --version`
3. If you didn't get a version then type in your terminal
4. `sudo apt update`
5. `sudo apt install git`

## Node

### Node On Mac

- press `command` and `space` and type `terminal` then click `enter`
- in the `terminal` type `node -v` if you got a version then you already have
  it.
- If you didn't get a version just then you need to install `Homebrew` if you
  don't have it already
- paste this in your terminal and click `enter`

  ```markdown
  /bin/bash -c "$(curl -fsSL
  https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
  ```

- after you installed `Homebrew` , use the command `brew install node` to
  install node.

### Node on Windows

- click on the `search` icon and type `cmd`.
- type `node -v` if you got a version then you already have `node`
- if not [install node for Windows](https://nodejs.org/en/download)

### Node on Linux

- It depends on your distribution, if you are using `Ubuntu`
- open your terminal and type `node -v`
- if you didn't get a version then
- `sudo apt update`
- `sudo apt install node.js`
- `sudo apt install npm`

## Install ZSH for Linux and Mac with bash terminal

- Check if you already have zsh

```Markdown
zsh --version
```

### Install `zsh`

Ubuntu

```Markdown
sudo apt install zsh
```

Mac

```Markdown
brew install zsh
```

### Make `zsh` Your Default Terminal

Ubuntu

```Markdown
 chsh -s $(which zsh)
```

Mac

```Markdown
<!-- for Apple chip -->
chsh -s /opt/homebrew/bin/zsh

<!-- for Intel ship  -->
chsh -s /usr/local/bin/zsh
```

- Restart your laptop

- Install `ohMyZsh`

```Markdown
sh -c "$(curl -fsSL
  https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

- [MORE INFO](https://github.com/ohmyzsh/ohmyzsh)

## Make Git Bash Default Terminal for VS Code

### Windows

- [CLICK HERE](https://www.youtube.com/watch?v=PzJCwfYfIzY)

## Add VS Code to The Path

> adding VS code to the path allows you to open your VS code form the terminal

### Windows or Linux

- press `Ctrl + shift + p`
- type `Shell Command`
- select `Shell Command: Install 'code' command in PATH`

### Mac

- press `command + shift + p`
- type `Shell Command`
- select `Shell Command: Install 'code' command in PATH`
