# Setting Up Your Environment

Before you can use git, you gotta have git. Simple, right? Now, depending on the platform you're working from you might have to install it, so here's a few different ways to get git installed and running on your machine:

## Windows + git Bash

This is straightforward, just head to [this site](https://git-scm.com/downloads) and select Windows to get the installer. This will install git as well as a modified version of MinGW (a terminal emulator of sorts for Windows, kinda anyway) and a GUI tool for working with git, though the latter isn't great (we'll address this in a bit).

## Windows + WSL

This is my preferred way of working with git on Windows, mostly cause I'm so used to Linux environments that it makes me feel more "at home". First you'll want to head to [this documentation](https://docs.microsoft.com/en-us/windows/wsl/install-win10) to see how to set up WSL support on Win10 and then you can visit the Windows Store to find your flavour of Linux that you wish to work with. Personally I use [Ubuntu under WSL](https://www.microsoft.com/en-au/p/ubuntu/9nblggh4msv6) cause it's all you really need and just works. There's also [Debian](https://www.microsoft.com/en-au/p/debian/9msvkqc78pk6) which works great and many other environments you can install. Honestly though, this isn't something I would super stress over since it will only form a smaller part of your overall workflow.

## MacOS with Homebrew

Go to [this site](https://brew.sh/) and follow the instructions to install Homebrew. Once installed and properly setup, run `brew install git` and you're off to the races!

## Linux

Depending on your distro you'll need to use a different package manager (eg. Debian/Ubuntu have `apt`, Arch has `pacman`, CentOS has `yum`, etc.). Chances are if you're using Linux then you probably already have an idea on how to install packages using your package manager of choice, but just to give a few examples:

### Debian/Ubuntu

```
$ sudo apt install git
```

### Arch

```
$ sudo pacman -S git
```

### CentOS

```
$ sudo yum install git
```

Refer to your disto/package manager isn't listed here.

## GUI Wrappers

A common tool we see these days in the git ecosystem are GUI wrappers. That is, GUI applications that simply act as an interface to git. It's still running the same commands you normally would under the hood, but now you just press buttons to make things happen. I personally believe that once you know what you're doing and what you're looking for GUI wrappers can be a really good tool to have under your belt. However, to understand git I feel like getting dirty with the CLI for it helps a lot since there's nothing abstracted away and you're in full control. It sounds scary, but trust me it's not!

All the same, if you wish to go the GUI wrapper route here's a few that I've personally or mates I know have used and can recommend:

### Sourcetree (Windows/MacOS)

Sourcetree is a solution from Atlissian, the same people behind dev tools such as Bitbucket and Jira. Not much more to say about it, if you want to try it out you can get it from [here](https://www.sourcetreeapp.com/).

### GitKraken (Windows/MacOS/Linux)

My GUI wrapper of choice, being that it's free to use and on both Windows and Linux which is always real nice. Integrates pretty well with many git hosts like GitHub, Bitbucket, and GitLab. If you want to try it out you can get it from [here](https://www.gitkraken.com/)

### Fork (Windows/MacOS)

Not something I personally use or have ever used, but one of my mates swears by it so I thought I might as well add it here. You can pick it up [here](https://git-fork.com/)

All of these applications simply add a GUI layer on top of the git CLI so they'll have the same core functionality, the main differences you'll see is in ease of use, information it presents to you, that sorta thing. For now I wouldn't stress much about what it is you use, just that you use it and stick with it. Bear in mind however that I will be covering everything in the git CLI tool since it will apply to every platform, and like I mentioned before I personally feel like learning git on the CLI will give you a better idea of how git works so that you have better control over it as you work with it.

So now we have our environment set up, lets start using git!
