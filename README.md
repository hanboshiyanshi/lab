# lab
实验室问题总结

# 使用方法说明
1. 先fork项目到自己的github中
2. 在本地 git clone "https://github.com/lxsyz/lab-1.git" (lxsyz是我的账号，把fork后的仓库下载到本地)
3. 本地修改，更新你整理的问题和解决方案
4. git add .  添加内容到暂存区
5. git commit -m "添加说明"  本地提交
6. git remote add upstream "https://github.com/hanboshiyanshi/lab.git" 添加上游源库
7. git status查看本地状态， git remote -v查看远程库状态

# 提交方式
法一: git push -f upstream master 强制提交到上游源库
法二: git push origin master 提交到自己的仓库中,然后发起PR由源库管理员审核通过
