Today:
1. git pull
2. git rm --cached <file>  // to unstage
3. git add
4. git status
5. git init
6. git log
   git log -p -2
   git log --author
   git log --oneline
   git log --graph
   git log --pretty=oneline
   git log --pretty=format
   git log --oneline --graph
   git log --oneline --graph --all
   git log --oneline --graph -[number] 
7. git diff
   git diff --stage
8. git mv
9.  git rm
10. .gitignore
	/foldername
	*.log
	*.zip
	git rm -r --cached // for ignore already tracked files
10. git checkout --[filename] // 恢复到上一次的状态， have not add and commit
    git restore <file>..." to discard changes in working directory) // new 
11. git reset HEAD [filename] // 撤销当前文件的追踪 already add to stage, then use git restore to original vision
12. git reset --hard HEAD^  // 回退到上一个版本
13. git reset --hard HEAD^^ // 回退到上上一个版本
14. git reset --hard HEAD [hash ID] // // 回退到指定hash ID 的版本
15. git refolg  // 	
16. git checkout [hash] --[filename]
17. git branch [name]
    git checkout [branch name]
    git checkout -b [branch name]
	git branch [name] -d
	git branch [name] -D
18. git merge [branch name]
19. conflict:
    git merge [btanch name]
    git status // check the reason of conflict
    git merge --abort // 忽略合并
    手动选择正确内容
    git add 
    git commit
20. git merge branchnae --no-off
    git merge branchnae --no-off --no-commit [branchname]
    git merge branchnae --no-off --squash [branchname]
    git merge --squash [branchname]
    git reset --hard ORIG_HEAD
21. git push origin main

    