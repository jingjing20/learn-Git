# Git

极课时间玩转 Git

- 重命名暂存区文件名
  `git mv oldName newName`

- 删除本地分支命令
  `git branch -D BranchName`

- 删除远程分支命令
  `git push origin --delete BranchName`

- 修改 **最近一次** commit 描述信息
  `git commit --amend`

- 修改**历史** commit 描述信息
  `git rebase -i commit id`(这个 commit id 必须是修改对象的父节点以上)

- 在本地新建远程仓库已有的分支
`git checkout -b 分支名 origin/分支名`  然后再 `git pull` 一下