# Demo

Learning how to use GITHUB

## Some Github commands

learning about some of the git commands

git clone, git add, git commit, git status, git push, git pull, git init

### Creating and adding SSH

ssh-keygen -t ed25519 -C typeyouremailhere@email.com

ssh-agent bash   (this will activiate the ssh)

ssh-add ~/.ssh/id_ed255192

### Git branching

Feature branches are used to work on little porjects/changes without changing the master branch. 

git branch -> checks to see different branches. * indicates that you are currently on that branch

git chcekcout -> used to check other branches

git checkout -b featurebranchname -> creates a branch with the featurebranchname

git diff -> shows the changes that has been made between two features

git chckout -d featurebranchname  -> delete featurebranchname

git commit -am "msg" -> add and commit

git reset -> undo/reset add

git reset HEAD~1 -> reset latest commit

git log -> show list of all commits

git reset numberfromthelistofcommits -> will reset to the commit that is mentioned.

git reset --hard numberfromthelistofcommits -> will reset all of the commits, add, and files up until the numberfromthelistofcommits

HOWTO
1.  pushing from a feature branch will feature branch will create a fatal error. Current featurebranch has no upstream branch. Use the link provided in error to successfully push.  git push --set=upstream origin featurebranch

2. We have no created PullRequest(PR) on Github. We can now edit, comment, or review the request. Once the feature branch is pulled/merged, the feature branch is no longer required and ready to be deleted.

Sometimes the feature branches will create merge conflicts when there are multiple changes happening in the master branch.

#### Git forking

Copy a repo from yourself or other people's github. You could then make changes and pull request back to the original repo.


https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
Here is a markdown cheatsheet :) 

```python
def print_fun():
  print("Markdown is fun!")

print_fun()
```
