# GIT CheatSheet
 
 Basic GIT operation requires 5 actions to perform .
 - GIT Clone : To clone from remote to local . It's one time activity 
 - GIT Add : Developer needs add files in GIT local repository
 - GIT Commit : It's kind of saving with a version no (sha-2 key)
 - GIT Push : Developer needs to push back stable code in GITHUB (GIT Remote repository)
 - GIT Pull : Everyday / Before you start developement , you should pull once so that you get latest code in your working dir.

## Example of basic commands 

git clone --branch [Branch Name][Repository URL]
**eg :** git clone --branch Feature git@git.build.inter.ikea.com:ikeapfubi/IDW.git - To clone a specific repo :
Feature: Branch Name   
git@git.build.inter.ikea.com:ikeapfubi/IDW.git: Repository URL


git add <file name>
eg : git add README.md / git add .

git commit -m " Proper message ie CR NO or #JIRA STORY ID - EXTRA TEXT IF YOU WANT " 

git push origin Feature 

git pull <> Everyday : Your local repo/working dir is updated  

<< to compare files on remote branch
git log 
git status 
git diff Feature remotes/origin/(Feature/PREPROD/master) README.md 

>>