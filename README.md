# git-lab

Git 学习练习仓库。用来跑通「本地 → GitHub」的完整流程。

## 已完成动作

```powershell
git init -b main
git add .
git commit -m "feat: 初始化练习仓库"
git remote add origin git@github.com:lueluelueluelueluelue001/git-lab.git
git push -u origin main
```

## 常用命令备忘

| 目的 | 命令 |
|---|---|
| 看状态 | `git status` |
| 看改了哪几行 | `git diff` |
| 加入暂存区 | `git add 文件名` / `git add .` |
| 提交 | `git commit -m "说明"` |
| 看历史 | `git log --oneline` / `git lg` |
| 推到远程 | `git push` |
| 拉取更新 | `git pull` |
