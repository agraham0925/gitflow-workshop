# Git and Gitflow Workshop
<!-- Created by [Alyssa Graham](https://github.com/agraham0925) and [Marie Trull](https://github.com/marietrull) to help web development students practice the gitflow process in a team setting. -->

<!-- ## FIRST TASK
* person1 - in index.html on line 8, add input field with button that will update the page to display members of your group. Make a commit.
* person2 - in index.html on line 8, add an h1 that says "This is Gitflow Practice" Make a commit.
* person3 - in index.html on line 8, add a ul tag list of types of dogs.


## SECOND TASK
* person1 - in index.html, add a p tag with some text of your choice.
* person2 - in index.html, add an h2 tag with the text "Group Mates". add an ul tag with all the names of the people in your group.
* person3 - in index.html, add a ul with a list of movie titles.
-->

## GIT FLOW + COMMON COMMANDS
### Create Branch
* `git branch`
* `git branch [branchname]`
* `git checkout [branchname]`
* OR instead of the two separate commands, you can do `git checkout -b [branchname]`

### Complete Task + Commit 
* `git status`
* `git add .` OR `git add -A`
* `git status`
* `git commit -m "Commit Message"`

### Push to Remote
* `git push -u origin [branchname]`

### Pull Request
* Go to GitHub and click on branches
* Find your [branchmame] 
* Create pull request
* **SOMEONE ELSE** - 1-2 group members should approve your pull request and merge the branch/pull request into the remote master branch

### Pull the Updated Remote Master & Get the Changes onto Your Branch
**For everyone else in your team who needs the updated Master** 
* commit changes on your local branch (see Complete Task + Commit)
* `git checkout master`
* `git branch` (ALWAYS do this to confirm which branch you're on!)
* `git pull`
* `git checkout [branchname]`
* `git branch` (ALWAYS do this to confirm which branch you're on!)
* `git merge master`
* resolve merge conflicts + repeat

### add'l resources for practicing git and git flow:
* https://github.com/jlord/git-it-electron#what-to-install
* https://www.atlassian.com/git/tutorials/comparing-workflows
* https://github.com/praqma-training/git-katas/blob/master/Overview.md
* https://github.com/praqma-training/git-katas

### reading resources:
* https://medium.com/@muneebsajjad/git-flow-explained-quick-and-simple-7a753313572f
* https://www.freecodecamp.org/news/beaucarnes/how-to-use-GitHub--7mdMGAPL
* https://medium.freecodecamp.org/what-is-git-and-how-to-use-it-c341b049ae61
* https://medium.freecodecamp.org/how-to-become-a-git-expert-e7c38bf54826
* https://medium.freecodecamp.org/how-to-use-git-efficiently-54320a236369
* https://medium.freecodecamp.org/5-github-tips-for-new-coders-2f312689ffd5 
