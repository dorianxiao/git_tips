## Git tips

1. ```git init ```：初始化git目录
2. ```git add README.md```：添加文件到暂存区
3. ```git commit -m "这是注释"``` ：提交到本地仓库
4. ```git status```：查看提交状态
5. ```git diff README.md```：查看不同
6. ```git log```：查看提交记录，一行查看 ```git log --pretty=oneline```
7. ```git reset --hard HEAD^```：回退到上一个版本，```git reset --hard HEAD~100```，回退100个版本
8. ```git reflog```：查看版本号
9. ```git reset --hard 6fcfc89```：恢复到某个版本
10. ```git checkout -- README.md```：撤销工作区的修改
11. ```git remote add origin https://github.com/dorianxiao/git_test.git```：新增远程主机
12. ```git push -u origin master```：第一次把当前分支推送到远程，以后省略```-u```
13. ```git clone https://github.com/dorianxiao/git_test```：克隆到本地
14. ```git checkout -b dev```：创建并切换到分支，等于```git branch dev, git checkout dev```
15. ```git branch```：查看分支
16. ```git merge dev```：在master分支上合并```dev```分支
17. ```git branch -d dev```：删除分支
18. ```git stash```：隐藏当前分支，等其他分支完成后可```git stash pop```恢复并删除该```stash```
19. ``git stash apply``：恢复分支但不删除，```git stash drop```：删除
20. ```git stash list```：查看所有stash
21. ```git remote```：查看远程库信息，```git remote -v```：详细信息
22. ```git branch -r -d origin/fenzhi1``` + ```git push origin :fenzhi1``` ：删除远程分支
