
# Recommended Stack


## Install Ubuntu


1. Install Ubuntu 14.04 LTS on your machine, either natively or in a VirtualBox, VMWare or Parallels virtual host.
2. Run on the command line:

```
sudo apt-get upgrade
sudo apt-get install -y build-essential
```

If you want to be able to ssh into your box from your virtual host:

```
sudo apt-get install openssh-server
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
- consider installing the packages (open quick launch with cntl-shift-p, type pcip [a short form for package control install package], press return, then type the name of the package you want):
  - git gutter
  - bracket highlighter
  - SublimeLinter
- edit your User settings (Preferences -> Settings - User):

```
  {
    "draw_white_space": "all",
    "rulers": [100],
    "tab_size": 2,
    "translate_tabs_to_spaces": true
  }
```

To get started, read [https://blog.generalassemb.ly/sublime-text-3-tips-tricks-shortcuts/]().
And for more detail: [Sublime Text Unofficial Documentation](http://docs.sublimetext.info/en/latest/)

## Preparing your Project

### Licensing


Every project must have a license. Unless you have strong reasons to use a different license, use the [MIT license](./sample-LICENSE). Copy that file to your project, add the copyright date and your name, and rename to 'LICENSE'.

We chose the MIT license because it is a BSD-style license. Read up on licensing here:

- [the-whys-and-hows-of-licensing-scientific-code](http://www.astrobetter.com/blog/2014/03/10/the-whys-and-hows-of-licensing-scientific-code/) 
- [BSD pitch](http://nipy.sourceforge.net/nipy/stable/faq/johns_bsd_pitch.html)
