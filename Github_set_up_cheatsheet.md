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

``` git branch``` *shows which branches exist, in this case main and new-feature. the green color indiicates the branch I'm currently on*

![Screenshot 2023-10-11 at 1 59 39 PM](https://github.com/novatr9/Misc/assets/133291499/91c4417b-a64d-4955-9487-f92c4f4994b2)

```git checkout new-feature``` *jump to the new-feature branch*

![Screenshot 2023-10-11 at 2 02 09 PM](https://github.com/novatr9/Misc/assets/133291499/62c7fabd-3c7d-43c0-93e0-7c259d927111)

```git branch``` *let's check*

![Screenshot 2023-10-11 at 2 03 04 PM](https://github.com/novatr9/Misc/assets/133291499/ec4a0119-54e0-4ed0-9bac-1f796775bf19) *it worked!*

## 3. Makes changes

### 3.1 Add a file
