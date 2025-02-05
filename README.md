git.conf
========

My personal configuration for git 🏷️

Reasons
-------

When getting git program (mainly on Linux Distros), you can have some
default git configurations, such as:
- no user name
- no email
- weird printting with `git log`
- ...

To solve this, I've created this repo which you can update these
configurations:

> [!WARNING]
>
> All these changes have a global effect!
>
> If you're not sure about any command, I recommend not following it!

Commands
--------

Open your terminal and run these following commands: (Git is
required, obviously)

```shell
# change default branch name (on init) to main
git config --global init.defaultBranch main

# change user credentials
git config --global user.name "<YOUR_USERNAME>"    # name
git config --global user.email YOUR.USER@email.com # email

# print colored text when git log or something like this
git config --global color.ui auto

# no '~' prints on entire shell when git log
git config --global pager.log false
```
