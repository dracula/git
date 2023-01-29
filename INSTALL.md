### [Git](http://git-scm.com/)

#### Introduction

According to [Git documentation](https://git-scm.com/docs/git-config) valid colors are limited to white, black, green, magenta, blue, cyan, yellow, red.
Due to the limitation on colors availablility, it appears the best option is to theme your terminal, then adjust the .gitconfig file

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

    git clone https://github.com/dracula/git.git

#### Install manually

Download using the [GitHub .zip download](https://github.com/dracula/git/archive/master.zip) option and unzip them.

#### Install using [Homebrew](https://brew.sh)

Easily install from [dracula/homebrew-install](https://github.com/dracula/homebrew-install/blob/main/Formula/dracula-git.rb):

    brew tap dracula/install
    brew install --formula dracula-git
    # then, to activate:
    git config --global include.path /usr/local/opt/dracula-git/gitconfig

#### Activating theme

1. Install the Dracula theme on your terminal.
- [Alacritty](https://draculatheme.com/alacritty)
- [Fluent Terminal](https://draculatheme.com/fluent-terminal)
- [Foot](https://draculatheme.com/foot-terminal)
- [Gnome Terminal](https://draculatheme.com/gnome-terminal)
- [Hyper](https://draculatheme.com/hyper)
- [iTerm](https://draculatheme.com/iterm)
- [Kitty](https://draculatheme.com/kitty)
- [Terminal](https://draculatheme.com/terminal)
- [Terminator](https://draculatheme.com/terminator)
- [Termite](https://draculatheme.com/termite)
- [Termux](https://draculatheme.com/termux)
- [WezTerm](https://draculatheme.com/wezterm)
- [Windows Terminal](https://draculatheme.com/windows-terminal)
- [Xfce4 Terminal](https://draculatheme.com/xfce4-terminal)

2. Determine the directory for the Git config file. The default location is `~/.gitconfig`. In some environments, a user’s configuration will be stored in the alternate location `$XDG_CONFIG_HOME/.gitconfig`.

3. Copy the content of this repositorie’s config file (`config/gitconfig`) into your Git config file.
