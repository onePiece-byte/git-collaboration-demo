# git-collaboration-demo
git分支和pr协作实验

## Git 协作实验

本项目用于学习 Git 分支管理与 GitHub Pull Request 协作流程。

### 实验参与者

- A：仓库所有者，负责代码审核与合并
- B：huangjunyi，负责功能分支开发与代码提交

### B 的开发任务

1. 从 main 分支创建 feature/huangjunyi-B 分支。
2. 在功能分支上修改 README.md 文件。
3. 使用 Git 提交本地修改。
4. 将功能分支推送到 GitHub。
5. 创建 Pull Request，请求 A 进行代码审核。
6. A 审核通过后，将功能分支合并到 main 分支。
7. A 和 B 分别执行 git pull origin main，同步最新代码。
8. 使用 git log --oneline --graph --all 查看合并后的提交历史。
