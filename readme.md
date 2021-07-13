# Git and Git-Bash

When you're using Github Desktop, you're actually using an abstracted version of `git`, a command app/interface. Although Desktop makes it very easy for you to manage your Git repository, it is `git` that offers you the most power and versatility over the repo. When you truly understand how Git works, you'll only need `git` in your toolbox.

Linux users likely have `git` in the terminal already. MacOS and Windows users must install it externally (https://git-scm.com/downloads).

## Basic Git Commands

You've probably already known how to copy or create new git repos in Github Desktop, but it's not half as hard on `git`. You will see a lot of similar vocabulary between Github Desktop and `git`:

```
($ = command; // = comment; <> = replace with user input)

// initialize a directory as a local git repo (used for new or existing folders)
$ git init

// "stage" all project files to be committed
$ git add .

// commit changes with a message
$ git commit -m "<commit_message>"

// push the commit from local to github
$ git push

// fetch changes from github
$ git fetch

// pull changes from github to your local repo
$ git pull

// clone a github repo to your computer
$ git clone <git_link>

// link local repo to an existing github repo
$ git remote add <git_link>
```

## Caveats & Troubleshooting
`git` (and Github Desktop) does not automatically sync files from Github and vice versa; make sure to **commit, push, fetch, and pull** your repo when working on your project. It is also possible to store multiple commits before pushing--some people do that for some reason. Finally, if you have any more problems, always try looking for a solution on google and StackOverflow. If nothing works, make another github repo lol.