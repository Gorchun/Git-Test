# Git-Test
## Just A Note About Git
---
***Geneally Instructions：***

***First Step:(get a repo and start cooprating with your friends)***

git clone [repository name]  //clone repo, repo can be an URL or IP[:port]

git clone https://github.com/Gorchun/Git-Test.git

git clone 202.202.43.125/Example.git


***Second Step:(pull updates from other if it exists)***

git pull [origin branch-name] // 'origin here' represents repository name that you cloned. And 'master' is a default branch in remote repo.

git pull origin master  //pull files in the branch of master 
git pull origin Gorchun //pull files in the branch of Gorchu
n


***Third Step:(add local file to stash when you want to commit your changes)***

git add + filename //add your local file to stash

git add Readme.md  //add 'Readme.md' file

git add . // The charcter '.' here represents all files in this directory


***Fourth Step:(commit changes)***

git commit -m ['your advice or notice']

git commit -m 'Change Readme.md'


***Fifty Step:(push to remote repo)***

git push [origin branch-name]

git push [origin branch-name1 : branch-name2]

git push origin master //use your local master branch to update the master branch of the remote repo

git push origin master:Gorchun //use your local master branch to update the Gorchun branch of the remote repo

***Other Useful Instructions:***

git log // use in your local directory (cmd), and you can get all the commit informations before your current version.

***Note:***

1.If your want to commit your change to remote repo, make sure that you have the authority. Or remote repo will refuse your commit.

2.Before you push, you must pull the changes first. Or you will fail to push if there is a new change commited from others.


***Write Your Name here:***

| name  | date  |
| :--:  | :--:  |
| Gorchun  | 2019.09.23  |
