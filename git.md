
git commit -m "wrote a commit log infro"
如上命令可以把暂存区里的文件提交到仓库。git log
如上命令可以查看提交日志，可以看到当前 HEAD 之前的所有提交记录。git reset —hard HEAD^
git reset —hard HEAD^^
git reset —hard HEAD~100
git reset —hard 128个字符的commit-id
git reset —hard 简写为commit-id的头几个字符