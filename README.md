

git push origin :main
删除原先main分支

然后在分支里面直接改名





git branch -m main <BRANCH>
git fetch origin
git branch -u origin/<BRANCH> <BRANCH>
git remote set-head origin -a
