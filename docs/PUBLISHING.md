# 维护与发布

仓库：[htj90064-design/terraria-guide-pet](https://github.com/htj90064-design/terraria-guide-pet)

简介：`Unofficial Terraria Guide pet for Codex v2 — 9 animations and 16 gaze directions.`

建议主题：`terraria`、`codex`、`virtual-pet`、`pixel-art`、`spritesheet`。

## 获取项目

```sh
git clone https://github.com/htj90064-design/terraria-guide-pet.git
cd terraria-guide-pet
```

也可以通过仓库页面的 **Code → Download ZIP** 下载。安装步骤见 [README.md](../README.md)。

## 提交后续更新

在工作目录没有未提交更改时，先同步远程分支：

```sh
git pull --ff-only origin main
```

完成修改后，同步更新相关说明、预览和 `SHA256SUMS.txt`。校验清单包含除清单本身以外的项目文件，使用 SHA-256 和仓库相对路径，不包含 `.git`。提交前检查暂存内容：

```sh
git add .
git diff --cached --stat
git diff --cached --check
git commit -m "Update Terraria Guide pet"
git push origin main
```

推送后检查仓库文件及 README 中的动画预览。不要将本地配置、API 密钥、工作日志或生成缓存加入仓库。

## 可选 Release

如果需要 Release，可以使用 `v1.0.0` 作为首次发布标签，上传另外准备的宠物安装包 `terraria-guide-v1.0.0.zip`。安装包只含 `terraria-guide/pet.json` 和 `terraria-guide/spritesheet.webp`。

GitHub 源码仓库应上传展开的项目文件。`terraria-guide-github.zip` 是整份项目的便携打包，不需要作为仓库中的一个大 ZIP 提交。

许可状态见 [LICENSE.md](../LICENSE.md)。不要在创建仓库时额外选择一个会被理解为覆盖 Terraria 美术资源的统一许可证。
