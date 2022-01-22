git init
git add readme.txt
git commit -m "wrote a readme file"
git log
git reset --hard HEAD^ 版本回退
git reflog
git status
git diff HEAD -- readme.txt 查看工作区和版本库里面最新版本的区别
git checkout -- readme.txt 丢弃工作区的修改
git restore <file> 丢弃工作区的修改
git reset HEAD readme.txt 丢弃暂存区的修改
git restore --staged <file> 丢弃暂存区的修改

