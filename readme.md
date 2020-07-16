# Git

极课时间玩转 Git

- 重命名暂存区文件名
  `git mv oldName newName`

- 删除分支命令
  `git branch -D 分支名`

- 修改**最近一次** commit 描述信息
  `git commit --amend`

- 修改**历史** commit 描述信息
  `git rebase -i commit id`(这个 commit id 必须是修改对象的父节点以上)
