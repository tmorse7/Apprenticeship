---
title: Git and Github Notes
layout: default
---

# Git and Github Notes

* Repository
	- Place to store files
* Commit (command)
	- "Save" (update)
	- Hash
		~ Crazy number after commit
* Branch
	- Master
		~ Main branch
	- Branches go off of master branch and off of each other
* Pull Request
	- Take changes from one branch and bring it to another
	- Ask to pull something into someone else's repository
* Merge
* Fork
	- Duplicate a repository from another person to work on something without interfering with the main repository
* clone (command)
	- Taking a repository and copying it to your computer
* status (command)
	- Gives you repository info
* commit arguements
	- (-a) commits all
	- (-m) commits with message (after -a)
* Sign in
* Git config --list (shows git config)
* log
	- local history of commits
	- gets into VIM
* Push (command)
	- Sending to github
* Pull (command)
	- Recieving from Github
* Remote (command)
	- Where it sends files
	- (-v) shows url of where it's going
* Push Syntax
	- push (remote) (branch)
	- remote is usually origin when you clone
* git init
	- Make a folder a git repository
* Locally, in order to make changes:
	- Save
	- Add (puts things in a staging area to actually get commited)
	- Commit
* If you start repository locally, get remote from github
* If you need to log back in, use these:
	- git config --global user.name "Your name"
	- git config --global user.email you@example.com
* Github Pages
	- make a new branch called "gh-pages"
	- Change default repository in settings under branches
	- Delete master branch
* git checkout -b
	- Creates new branch
* git diff
	- Exact changelog
* git checkout "blah"
	- Switches branches
* git branch -v
	- Lists all branches

# Process:

* 'git init' to initialize folder or 'git pull <link> <branch>'
* Make a branch if need be with 'git checkout -b "branch"'
* Set remote properly with 'git remote' and if you don't have it, use 'git remote add origin <link>'
* Edit something with VIM or Atom
* Add to stage with 'git add <file>'
* Check 'git status' if need be to see if stage is correct
* Commit file with 'git commit (-a is optional) -m "comment"'
* Push file out with 'git push -u origin <branch>'

In order to access shared folder, you need to go to root and then access vagrant folder.

In order to push something with ssh, use the 'gitssh' folder instead of origin
