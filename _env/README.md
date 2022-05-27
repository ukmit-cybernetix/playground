# Development Environment

### Tools For Your Device

Download and install the tools below:

1. [Discord](https://discord.com/download)
2. [Visual Studio Code](https://code.visualstudio.com/download)
3. [Git](https://git-scm.com/downloads)

> **Note**
> When you install Git
> please change the default editor used by git to: _Use Visual Studio Code as Git's default editor_.

### Join Discord Community Server

Following the steps below:

1. Join Discord Community Server: **UKM IT CYBERNETIX**
2. We will do activities on the category channel: **CX-MINI-COURSE**
3. Following the rules on that channel

### Create Github Account

Following the steps below:

1. Visit this [Github](https://github.com)
2. Signup using your Gmail Account
3. Request for Join Github Organization: [UKM IT Cybernetix](https://github.com/ukmit-cybernetix)

### Setup Git & Github

Following the steps below:

1. Set up git with your user name and email
2. Open a terminal/shell and type:

   ```
    $ git config --global user.name "Your name here"
    $ git config --global user.email "your_email@example.com"
   ```

3. Check your config:

   ```
     $ git config --list
   ```

### Setup Workspace

Following the steps below:

1. Create folder with the name _ukmitcybernetix_
2. Create repository with the name _CX(Generation)-(CalledName)_ , example (CX12-ARFAN)
3. Open a terminal/shell and type:
   ```
     $ git clone [your repository https/ssh]
   ```
4. Add playground remote upstream from url, [here](https://github.com/ukmit-cybernetix/playground.git)
   ```
     $ git remote add upstream https://github.com/ukmit-cybernetix/playground.git
   ```
5. Make sure you have 4 remote repositories:
   ```
     $ cd name CX(Generation)-(CalledName), example (cd CX12_ARFAN)
     $ git remote -v
         origin hhttps://github.com/ukmit-cybernetix/CX12-ARFAN.git (fetch)
         origin hhttps://github.com/ukmit-cybernetix/CX12-ARFAN.git (push)
         upstream  https://github.com/ukmit-cybernetix/playground.git(fetch)
         upstream  https://github.com/ukmit-cybernetix/playground.git(push)
   ```
6. Pull data from the remote upstream and then push it to your remote origin
   ```
     $ git pull upstream main
     $ git push origin main
   ```
   Make sure to check the changes before the push, so there is no conflict.

### Setup Check Point

Following the steps below:

1. Your Structure Folder:

   - 001_Git (Pull from playground)
     - folder: practice:
       - file task
       - file practice.md
     - folder: screenshot:
       - file image with extention _.png / .jpg_

2. Format File practice.md

```
# Resume

## Links
1. [Link Name](path)
2. [Link Name](path)

## Screenshots
![Name](path)
```
