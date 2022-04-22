# gitworkshopviit
git commands : git workshop vignan 06-04-21
# Git practice repo 

**Strong text**

***Strong emphasised text***

*Emphasised Text*

[facebook](www.facebook.com)

##ignore

[![image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT_gQ-dZXXplCmQWbaQHjSzp0UHThNXCrTaTg&usqp=CAU)](https://github.com/yihui/xaringan)

![image](https://github.githubassets.com/images/modules/open_graph/github-mark.png)

[![image](https://i.stack.imgur.com/NBaVX.jpg)](https://steamuserimages-a.akamaihd.net/ugc/536254120229165850/53700BDF7512E0E9E50E9493011D9D45DCFEAC47/)

* Android
  * Alpha
    * CupCake
      * Unordered List 

  1. Android
     1. Beta
       1. Cupcake
          1.Ordered List  

S.No    |  Name
        
--------|-------

01      | Android

02      | Beta

03      | Table

## to know hiddend files -> ```ls -a(this is without permission)```

##  to know all the files with permissions -> ```ls -la(this is with permission)```

## to know verion in git -> ```git --version```

## to initialize folder -> ```git init (hidden folder created like .git)```

## to check satuts of file -> ```git status```

## to change from untracked to staging area -> ```git add filename or git add .```

## to change from staging area to untracked -> ```git rm --cached filename```

## to change from staging to commit file -> ```git commit -m "commit message"```

## to give your username global -> ```git config --global user.name "name"```

## to give your useremail global -> ```git config --global user.email "email"```

## to give your username for specific dir -> ```git config user.name "name"```

## to give your useremail for specific dir -> ```git config user.email "email"```

## to get SHAkey,authorname,data and commit -> ```git log```

## to get short description of SHAkey -> ```git log --oneline```

## to change the head-master to another file -> ```git checkout SHAkey```

## to get back to master -> ```git checkout master```

## to change the commit message -> ```git commit --amend -m "commit message"```

## to delete latest commit -> ```git reset --hard HEAD^```

## to delete number of commits -> ```git reset --hard HEAD~number```

## to delete specific commit -> ```git rebase --onto branchname~(number to delete) branchname~(commit to keep as head) branchname```

## to clone -> ```git clone url```

## to clone and keep the filename -> ```git clone url filename```

## to get latest commit in clone url -> ```git log```

## to get initial commit in clone url -> ```git log --reverse```

## to count commits in url -> ```git rev-list HEAD --count```

## to get commits from initial to given date -> ```git log --until="date" or git log --oneline --until="date" (for short description)```

## to get commits from given date to end date -> ```git log --since="date" or git log --oneline --since="date" (for short description)```

## to get commits from given to given date -> ```git log --since="date" --until="date"or git log --oneline --since="date" --until="date"```

## to dispaly all remote repos -> ```git remote```

## to create remote -> ```git remote add variablename url```

## to dispaly all variablename and urls -> ```git remote -v```

## to push the files to remote -> ```git push variablename branchname```

## to pull the files from remote -> ```git pull variablename branchname```

## to check how amny branches present -> ```git branch```

## to create branch -> ```git branch newbranchname```

## to go to that branch -> ```git checkout branchname```

## to merge branches -> ```git merge branchname```

## to delete a branch after merge -> ```git branch -d branchname```

## to delete without merge and in local -> ```git branch -D branchname```

## to delete without merge and in remote -> ```git push remotename --delete branchname```

## to rename remote -> ```git remote rename oldremotename newremotename```

## to delete remote -> ```git remote remove remotename```

## to create branchname and checkout -> ```git checkout -b newbranchname```
