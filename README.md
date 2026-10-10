# Git 学习笔记

从零学习 Git / GitHub 的完整练习记录——2026 年 10 月，三天走完 Git 核心 + GitHub 协作全流程。

## 练习路线

| 阶段 | 练了什么 | 在本仓库哪里看 |
| --- | --- | --- |
| 1. 核心基础 | 三区域、add / commit / status / log / diff | hello.md 及其提交 |
| 2. 撤销与回退 | restore / reset / .gitignore | .gitignore（忽略 secret.log） |
| 3. 分支与合并 | fast-forward、三方合并（M 形） | git log 里的合并提交 |
| 4. 合并冲突 | 亲手制造并解决冲突 | shared.txt（A、B 两版共存） |
| 5. rebase 与 tag | 历史重写、直线化、版本标签 | rebase-demo 分支 |
| 6. GitHub 协作 | clone / push / fork / PR / 合并 | 已合并的 PR #1 |

根目录的各 .md 文件（hello.md、shared.txt 等）都是对应课程的练习产物。

## 看点：分支合并图

打开仓库页面的 **Network** 标签，或本地执行：

    git log --oneline --graph

可以看到亲手做出的 M 形合并图。

## 相关

- [我的 GitHub 主页](https://github.com/mazinging)
- [Hello-World](https://github.com/mazinging/Hello-World) fork 练习场（第一个 PR：octocat/Hello-World#11482）
