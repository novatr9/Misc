# Github set up cheatsheet

This markdown is meant to help any new user who already has a github.com account. Developers usually won't use the GitHub website on its own to make commits, branches, etc.
This cheatsheet is to explain how to clone repositories from github.com, make changes locally and then push the changes back to the remote repo.

## 0. Set up git

Most likely your computer will already have Git installed. (That's the language Github.com works with).
To check, use ```git --version``` in your terminal. The version number should appear.

If not, got to this [link](https://git-scm.com/downloads) to download.

## 1. Add identity

First step is to link your account locally. Let's say my user name on github is Newbie.
In my terminal, I would go:

```git config --global user.name Newbie```

```git config -- global user.email Newbie@newbnewb.com```

## 2. Clone Repo

Next step is to clone the repository from github you want to work on.

```git clone https://github.com/Newbie/test-repository.git```

![Screenshot 2023-10-11 at 11 26 57 AM](https://github.com/novatr9/Misc/assets/133291499/992fd8fc-ea78-4f05-b1c2-dd02a563f75c)

## 3. Change Directory and Make New Branch

```cd test-repository```

``` git branch new-feature``` *creates a branch called "new feature"*

``` git branch``` *check which branch you are on*
