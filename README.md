
# Recommended Stack


## Install Ubuntu


1. Install Ubuntu 14.04 LTS on your machine, either natively or in a VirtualBox, VMWare or Parallels virtual host.
2. Run on the command line:

```
sudo apt-get upgrade
sudo apt-get install -y build-essential
```

## SciPy

If you are using scipy, use [Anaconda](https://www.continuum.io/downloads). 

**Make sure you get Anaconda for Linux 64 bit, Python 3.5.**

This includes jupyter notebooks.

## Node

If you are using node:

```
curl -sL https://deb.nodesource.com/setup_5.x | sudo -E bash -
sudo apt-get install -y nodejs

```
See [full instructions](https://nodejs.org/en/download/package-manager/).


## Sublime

Consider using [sublime](https://www.sublimetext.com) as your text editor.

Configuration recommendations:

- install [Package Control](https://packagecontrol.io/installation#st2)
- edit your User settings (Preferences -> Settings - User):

```
  {
    "draw_white_space": "all",
    "rulers": [100],
    "tab_size": 2,
    "translate_tabs_to_spaces": true
  }
```

To get started, read [https://blog.generalassemb.ly/sublime-text-3-tips-tricks-shortcuts/]()






