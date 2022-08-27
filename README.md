
# Open Source Contribution

This repository will help you to contribute open source on Github. It will cover all the steps you need to follow to do any kind of open-source contribution.
## Install Git 
   Click Git 
[![Git](https://img.shields.io/badge/👨🏼‍💻Git-000?)](https://git-scm.com/downloads)

### Git setup
To avoid any sort of error follow the steps, After installing Git on your machine, Open a terminal and run the following git command:
- Github username
```
git config --global user.name "username"
```
- Github email
```
git config --global user.email "email@example.com"
```

## Fork this repo
Fork this repository by clicking the fork button. This will create a copy of this repository in your account.
<img src ='images/fork.png' width=400>

## Clone in your machine
Now go to your account and open the forked repository from your account and click on the code button, you will see a link to copy it.
<img src ='images/clone.png' width=400>
- Open a terminal and run the following git command:
**Example**
- step 1
```
git init
```
- step 2<br>
**link should be what you copied**
``` 
git clone https://github.com/your-username/opensource.git
```
- 2
```
cd opensource
```

## Create a branch
It is a best practice to create a new branch,
write this in your terminal:
```
git switch -c anyname
```

### Open name.txt file:
**without closing the terminal**
- 1: add your username and profile link of github in the below  **name.txt**
### Example
<img src='images/name.png' width=300><br>
## Last Part 
save the file and go to your terminal again:
```
git add .
```
make sure to use **' commas '** after -m
```
git commit -m 'added (username) in the name.txt'
```
write your username inside (username)
### Example:
```
git commit -m 'added (samadpls) in the name.txt'
```
#### Finally 
```
git push origin -u your-branch-name
```
if above command give u an error, try this instead:
```
git config --global push.autoSetupRemote true
```

## Go to your Github account
You will see the this <br>
<img src ='images/pull.png' width=400><br>
After merging it in your repository, open my repository again and create a pull request by going on the pull request option, then you will see this option<br>
<img src='images/pullreqbtn.png' width=300><br><br>
<img src='images/newpull.png' width=400><br>
set dropdown compare option and select your repo, and send pull request.<br><br>
<em>Congractulation now you know how to do opensource</em> <br><br>
Inspired by <a href='https://github.com/firstcontributions/first-contributions'>First-contribution</a>


