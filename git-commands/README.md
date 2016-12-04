#Git commands
Here are some basic git commands you may need.
- Most used commands, clone git, commit code and push changes.
- Branches, create prod and dev branches, merge branches.
- Config commands, show and update git configurations.


##Most used commands
Bring a git project to local computer
```
git clone <your git project url>
```
After make some changes, make one commit
```
git add -all
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
