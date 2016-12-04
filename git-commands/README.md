#Git commands
Here are some basic git commands you may need.
- Most used commands, clone git, commit code and push changes.
- Branches, create prod and dev branches, merge branches.
- Config commands, show and update git configurations.

##Config Git repository
```
export GIT_URL=https://github.com/weifengc/GitDummyRepo
export GIT_FOLDER=GitDummyRepo
```

##Most used commands
Bring a git project to local computer
```
git clone $GIT_URL
```
Go to the git project forlder
```
cd $GIT_FOLDER
```
Make some changes, eg. add one line to dummy.txt
```
echo "Dummy line added by $USER" > dummy.txt
```
Check current git status
```
git status
```
After make some changes, make one commit
```
git add --all
```
Give some description for the commit
```
git commit -am "Put some description here"
```
Push the change to server
```
git push
```

##Branches
Examples are copied from [here](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging). You can read it for details.

Create a new branch "newBranch"  using the latest commit
```
git checkout -b newBranch
```
Add one line to newBranch dummy.txt
```
echo "Add one line to newBranch by $USER" >> dummy.txt
```
Check out all branches you have
```
git branch
```
Switch to branch "master"
```
git checkout master
```
Merge newBranch to master
```
git merge newBranch
```
Delete branch newBranch
```
git branch -d newBranch
```




##Config commands
Show user name
```
git config user.name
```
Set user name to be weifengc
```
git config user.name "weifengc" 
```
Set user email to be bikeprogrammer@gmail.com
```
git config user.email "bikeprogrammer@gmail.com"
```
Set all git repository to be the same user name "weifengc"
```
git config --global user.name "weifengc"
```
