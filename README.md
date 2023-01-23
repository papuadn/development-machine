# A guide in setting up your development environment

[settings.zip](https://github.com/papuadn/development-machine/files/10475860/settings.zip)

- [Web Browsers](#web-browsers)
- [Git + GitHub](#git--github)
  - [2 Factor Authentication (2FA)](#2-factor-authentication-2fa)
  - [Basic Git setup](#basic-git-setup)
- [Mac](#mac-)
  - [PostgresApp](#postgresapp)
  - [PGAdmin](#pgadmin)
  - [Rectangle](#rectangle)
  - [Homebrew](#homebrew)
  - [`iTerm`](#iterm)
    - [Themes](#themes)
- [IDE's](#ides)
  - [JetBrains](jetbrains)

## Web Browsers

1. **`Safari`** 
2. **`Google Chrome`**
3. **`Google Chrome Canary`**
4. **`Firefox`**
5. **`Firefox Developer Edition`**
6. **`Brave`**
7. **`Microsoft Edge`**

## Git + GitHub

### 2 Factor Authentication (2FA)

[2FA](https://help.github.com/en/github/authenticating-to-github/about-two-factor-authentication)
protects your Github account
and also any organisations you are a member of
from malicious intent.

![setup-2factor-auth](https://user-images.githubusercontent.com/4185328/79356313-b16e9f80-7f36-11ea-8645-d0ee1ea36853.png)

### Basic Git setup   

Follow the official [**set up Git guide**](https://help.github.com/articles/set-up-git/) to get it working on your computer.

Setup 
[**ssh authentication**](https://help.github.com/articles/set-up-git/#connecting-over-ssh) 
as it is more secure and means you _won't have to type in your password every time you push to GitHub.

> **Note**: This also means that when you _clone_ a repo, you'll need to use the **SSH clone URL**. 

![change-to-ssh](https://user-images.githubusercontent.com/21698271/45860770-00daf280-bd37-11e8-92f8-34bb1ddf8152.png)

# Mac

## PostgresApp 
https://postgresapp.com/

## PGAdmin
https://www.pgadmin.org/

## Rectangle
Rectangle is window manager/tiler for Mac, it gives you keyboard shortcuts for moving/organising your apps/windows.

https://rectangleapp.com/

<img width="1115" alt="image" src="https://user-images.githubusercontent.com/194400/180993778-01d42389-9d9c-497c-a469-968e220ec3c7.png">

> **Note**: Rectangle will request/require "accessibility" permissions to control your windows. This is normal.

## Homebrew

Install homebrew [brew.sh](https://brew.sh), the package manager that will download and manage several other open source software packages.

Install with the following command in your terminal:

```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## `iTerm`

The default terminal emulator on Mac is _OK_ for basic tasks... <br />
We find that 
[**`iTerm`**](https://www.iterm2.com/) 
is _considerably_ better UX.
e.g: **`iTerm`** allows screen splitting:

![iterm-screen-splitting](https://cloud.githubusercontent.com/assets/4185328/9831158/56d8cb90-5943-11e5-99ec-9fb1a5907f8a.png)

As with Web Browsers, 
it doesn't _hurt_ to have more than one Terminal 
on your Mac. 

Download: https://iterm2.com

### Themes

There are _many_ themes 
which you may have heard of 
(like [Oh My Zsh](https://ohmyz.sh/)) 
that aim to add some functionality 
and shortcuts to your terminal. 
**We _don't_ recommend** 
you use any terminal themes 
when you're starting out
because they are a _distraction_
from the content/code you are crafting.

However, once you know what you're doing in the terminal, 
you can consider _enhancing_ your terminal with themes.
There are _many_ to choose from:
[iterm2colorschemes.com](https://iterm2colorschemes.com/)


<br />

# _Everyone_

The following applies to all people 
regardless of their operating system
(Linux, Mac & Windows)

## Text Editor

It's your choice which text editor you use, 
but you will inevitably need (at least) one editor.
At the time of writing, 
`@dwyl` we use 
[Atom](https://atom.io/) 
(Open Source, Electron/NodeJS based editor).

There are a wide range of text editors 
and integrated development environment (IDEs)
available.

We tend to use:

+ Atom: https://atom.io Open Source and has many plugins for language and framework support.
  Download and install it even if you only use it as a "backup" editor.
  VSCodium https://vscodium.com the Open Source version of VS Code. All Plugins work as expected
but no Tracking from Microsoft.
+ VS Code: https://code.visualstudio.com as a backup or read-only viewer when we are working on multiple projects concurrently.
+ Sublime Text: [sublimetext.com](https://www.sublimetext.com) - fast and free-ish 
  (you will be reminded to purchase a license ... but the license is perpetual not annual!)
  
  


### Basic text editor setup

**Set up** [**_soft tabs_**](https://opensourcehacker.com/2012/05/13/never-use-hard-tabs/) (indentation) <br />
You can usually set this up in the _Preferences_ or _Settings_ 
of your favourite text editor 
so you never have to think about it again 
(example below for [Atom](https://atom.io/)): 

<img width="507" alt="atom-soft-tab-preferences-menu" src="https://cloud.githubusercontent.com/assets/4185328/9154618/a6598690-3e91-11e5-939b-2c03cf3c7ffc.png">     


+ **Set up a guide (or line) to show on your page at the 80 character mark** so you know [when you go past 80 characters (or columns) on a single line](https://programmers.stackexchange.com/questions/604/is-the-80-character-limit-still-relevant-in-times-of-widescreen-monitors)
  + Useful for _readability_, particularly in code snippets where you would otherwise end up with a scroll bar
  + You should also be able to set this up in your favourite text editor's _Preferences_ (example below again on Atom editor - note, I also like to set up my editor to soft wrap at this line length so I can read other people's code more easily)    
  <img width="511" alt="80-character-line-guide-setup" src="https://cloud.githubusercontent.com/assets/4185328/9826015/45796748-58cf-11e5-8a5d-db7350a8eb82.png">
