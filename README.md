# GitTutorial

This is a tutorial for Git command. We hope it will be helpful for you.

## git pull | push

        `$ git init
        `$ touch .gitignore // create git ignore file
        `$ git add .
        `$ git rm -r --cached 文件/文件夹名称
        `$ git commit -m 'First commit.'

        `$ git remote -v       
        `$ git remote add origin ...git // ...git means the URL of the href location, for example: https://github.com/pedro-East/GitTutorial.git
        `$ git remote -v  // will show the url for you.
        `$ git remote remove origin  // remove the origin git
        `$ git remote add origin ...git 
          
        `$ git stash
        `$ git push -u origin master
        `$ git pull --rebase origin master

        `$ git checkout -b 分支名  #新建分支
        `$ git branch -a
        `$ git checkout 分支名
