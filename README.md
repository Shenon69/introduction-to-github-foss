# Welcome

# introduction-to-github

## Install Git on Your Local Machine

To install Git on your local computer, you need to [visit this link](https://git-scm.com/downloads).

> It's easy to install Git on Mac/Linux than Windows 😒

<br/>
1. Go to a Directory that you need to clone your Repository
   
> Ex: `D:\React`
<br/>
2. Right click & open `Git bash here` if you are a *Windows* user or Open `Terminal` if you are a *Mac/Linux* user in that directory location.
<br/>
<br/>
3. Type this command on it

```bash
git clone <Your-Repository-Url>
```


<br/>

You can find *Repository URL* from the top of the repository




> If you get any error while cloning the repo, please read this [Stack Overflow Forum](https://stackoverflow.com/questions/68775869/message-support-for-password-authentication-was-removed-please-use-a-personal)


# SetUp Git



**Download Git**: 

![Logo](https://git-scm.com/images/logo@2x.png)

- Download [git for Windows](https://github.com/git-for-windows/git/releases/download/v2.40.1.windows.1/Git-2.40.1-64-bit.exe).
- Download [git for Mac](https://git-scm.com/download/mac).
- Download [git for Linux & Unix](https://git-scm.com/download/linux).

## Git Configuration

```bash
git config --global user.name "John Doe"
```
```bash
git config --global user.email johndoe@example.com
```

So, let's get started!
## Git Commands

This command is used to obtain a repository from an existing URL.

```bash
Git clone <repository url>

```
Open repository in local storage

```bash
Cd <repository name>

```
Checkout a branch into your working tree


```bash
Git checkout -b name

```
```bash
git checkout branchname

```
List down branches

```bash
git branch

```
This command lists all the files that have to be committed.


```bash
git status

```
This command adds a file to the staging area.


```bash
git add .

```
This command records or snapshots the file permanently in the version history.


```bash
git commit -m 'commit message'

```

This command sends the committed changes of master branch to your remote repository.
```bash
git push

```
 - if we create a branch locally
  ```bash
git push --set-upstream origin <branch name>

```
This command is used to list the version history for the current branch.


```bash
git log

```
