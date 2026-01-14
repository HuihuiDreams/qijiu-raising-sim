---
description: 上传代码到 GitHub (qijiu-raising-sim)
---

# 上传代码到 GitHub

每次修改完代码后，执行以下步骤将更改推送到 GitHub 仓库。

## 步骤

// turbo

1. 查看当前修改状态：

```bash
git status
```

// turbo
2. 添加所有修改的文件到暂存区：

```bash
git add .
```

// turbo
3. 提交更改（请根据实际修改内容填写提交信息）：

```bash
git commit -m "更新: [简要描述本次修改内容]"
```

// turbo
4. 推送到 GitHub：

```bash
git push origin main
```

## 注意事项

- **远程仓库地址**: <https://github.com/HuihuiDreams/qijiu-raising-sim>
- 如果是第一次推送，可能需要先设置远程仓库：

  ```bash
  git remote add origin https://github.com/HuihuiDreams/qijiu-raising-sim.git
  ```

- 如果推送失败提示需要先拉取，执行：

  ```bash
  git pull origin main --rebase
  ```

  然后再次推送。

## 快速一键推送（可选）

如果想要一步完成所有操作，可以使用：

```bash
git add . && git commit -m "更新代码" && git push origin main
```
