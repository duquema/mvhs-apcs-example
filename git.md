# Git

## One Time Setup
	
`git config --global user.name "Max Duque"`
`git config --global user.email "duquem713@gmail.com"`

# Project Setup

`git init`
`touch .gitignore
Add `*.class` to the .gitignore file and save it.
`git add .`
`git commit -m "Initial commit"`
`git remote add origin "link"`
`git push -u origin master`

## 3 Step Repeating Commit Process
1. Make changes to code
2. Stage related changes
		* git add
3. Commit changes with a message
		* git commit -m "Message"

## Command
* status - > tell me what files have been staged or committed
* add -> add a file to the stage
* rm --cached -> remove file from stage
* git commit -m "Present tense description of what changed"
* git log - > show past commits enter to move down page
* checkout -- <file_name> -> discard recent changes

## Problem
* if commit without -m -> use Esc :wq to quit Vim
* wrong message -> git commit --amend -m "New message"
* wrong commit -> git checkout COMMIT_ID