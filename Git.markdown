命令行 | 说明
------|------
`git config --global user.name "Your Name"` | 对 Git 进行用户名设置
`git config --global user.email you@example.com` | 对 Git 邮箱进行设置
`git config --global push.default simple` | 设置 Git 使用当前分支为默认分支进行 Push
`git init` | Git 项目初始化
`git add -A` | 将项目所有文件纳入到 Git 中
`git commit -m "Initial commit"` | 保留改动并提交
`git remote add origin git@github.com:<username>/sample.git` | 添加远程代码库提交地址
`git push -u origin master` | 将代码推送到 GitHub
`git push` | 将代码推送到 GitHub
`git status` | 检查 Git 状态
`git log` | 显示 Git 提交记录（按 q 退出查看）
`git checkout -f` | 从代码库里检出代码，放弃当前文件修改
`git checkout master` | 将当前分支切换到 master 分支上
`git checkout -b static-pages` | 创建一个名为 static-pages 的新分支
`git merge fake-branch` | 合并分支
`git branch -d fake-branch` | 删除分支
