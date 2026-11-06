# 发布到 GitHub

建议仓库名称：`terraria-guide-pet`

建议简介：`Unofficial Terraria Guide pet for Codex v2 — 9 animations and 16 gaze directions.`

建议主题：`terraria`、`codex`、`virtual-pet`、`pixel-art`、`spritesheet`。

## 网页上传

1. 在 GitHub 新建一个空仓库，名称填写 `terraria-guide-pet`；不要自动添加 README、许可证或 `.gitignore`，本目录已经准备好了相关说明。
2. 选择上传现有文件，将本目录中的文件和子目录上传，保持层级。
3. 让 `README.md` 位于仓库根目录；不要再套一层 `terraria-guide-pet` 文件夹。
4. 提交后检查 README 中的 GIF 是否能显示。

网页上传时也应包括 `.gitignore` 和 `.gitattributes`。如果文件选择器没有显示隐藏文件，可以在仓库中另行添加这两个文本文件。

## Git 命令行

在此目录打开终端，先检查待提交内容：

```sh
git status --short
git diff --cached --stat
```

本地已初始化为 `main` 分支并暂存发布文件，尚未创建提交或设置远程仓库。确认 Git 的提交身份配置符合你的偏好后，创建提交：

```sh
git commit -m "Add Terraria Guide v2 pet"
```

在 GitHub 新仓库页面复制你自己的仓库地址，然后执行：

```sh
git remote add origin <你的仓库URL>
git push -u origin main
```

如果需要 Release，可以使用 `v1.0.0` 作为首次发布标签，上传另外准备的宠物安装包 `terraria-guide-v1.0.0.zip`。安装包只含 `terraria-guide/pet.json` 和 `terraria-guide/spritesheet.webp`。

GitHub 源码仓库应上传展开的项目文件。`terraria-guide-github.zip` 是整份项目的便携打包，不需要作为仓库中的一个大 ZIP 提交。

许可状态见 [LICENSE.md](../LICENSE.md)。不要在创建仓库时额外选择一个会被理解为覆盖 Terraria 美术资源的统一许可证。
