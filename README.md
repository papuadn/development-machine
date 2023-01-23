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
[**SSH authentication**](https://help.github.com/articles/set-up-git/#connecting-over-ssh) as it is more secure and means you won't have to type in your password every time you push to GitHub.

> **Note**: This also means that when you _clone_ a repo, you'll need to use the **SSH clone URL**. 

![change-to-ssh](https://user-images.githubusercontent.com/21698271/45860770-00daf280-bd37-11e8-92f8-34bb1ddf8152.png)

# Mac

## PostgresApp 
https://postgresapp.com/

## PGAdmin
https://www.pgadmin.org/

## Rectangle
Rectangle is window manager/tiler for Mac, that has keyboard shortcuts for moving and organising your apps and windows.

https://rectangleapp.com/

<img width="1115" alt="image" src="https://user-images.githubusercontent.com/194400/180993778-01d42389-9d9c-497c-a469-968e220ec3c7.png">

> **Note**: Rectangle will request/require "accessibility" permissions to control your windows. This is normal.

## Homebrew

https://brew.sh/

Install homebrew, the package manager that will download and manage several other open source software packages.

Install with the following command in your terminal:

```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## `iTerm`

https://iterm2.com/

The default terminal emulator on Mac is _OK_ for basic tasks...However, [**`iTerm`**](https://www.iterm2.com/) has a _considerably_ better UX.
e.g: **`iTerm`** allows screen splitting:

![iterm-screen-splitting](https://cloud.githubusercontent.com/assets/4185328/9831158/56d8cb90-5943-11e5-99ec-9fb1a5907f8a.png)

As with Web Browsers, it doesn't _hurt_ to have more than one Terminal on your Mac. 


### Themes

There are _many_ themes which can be used (such as [Oh My Zsh](https://ohmyz.sh/)) that aim at adding some extra functionality and shortcuts to your terminal. 

[iterm2colorschemes.com](https://iterm2colorschemes.com/)

## Text Editor

It's your choice which text editor you use, 
but you will inevitably need (at least) one editor.
At the time of writing, 
`@dwyl` we use 
[Atom](https://atom.io/) 
(Open Source, Electron/NodeJS based editor).

There are a wide range of text editors and integrated development environment (IDEs) available.

We tend to use:

+ Atom: https://atom.io Open Source and has many plugins for language and framework support.
  Download and install it even if you only use it as a "backup" editor.
  VSCodium https://vscodium.com the Open Source version of VS Code. All Plugins work as expected
but no Tracking from Microsoft.
+ VS Code: https://code.visualstudio.com as a backup or read-only viewer when we are working on multiple projects concurrently.
+ Sublime Text: [sublimetext.com](https://www.sublimetext.com) - fast and free-ish 
  (you will be reminded to purchase a license ... but the license is perpetual not annual!)

### Basic text editor setup

Prettier
ESLint
Plugins
