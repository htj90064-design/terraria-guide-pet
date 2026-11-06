# 参考来源

本项目的向导角色、名称和基本外观来自 Terraria。官方 Wiki 素材用于造型和动作参考，本仓库不附带下载的原始 Wiki 图片、视频、用户截图或解码视频帧。

## 主要造型参考

- [Terraria 官方 Wiki：向导](https://terraria.wiki.gg/zh/wiki/%E5%90%91%E5%AF%BC)
- [Guide.png 文件页](https://terraria.wiki.gg/wiki/File:Guide.png)：26 × 46 像素的向导原图，用于约束人物比例、发型、服装颜色和像素颗粒。

## 动作参考

- [Credits cutscene GuideRunningFromZombie.gif](https://terraria.wiki.gg/wiki/File:Credits_cutscene_GuideRunningFromZombie.gif)：官方 Wiki 页面中的片尾场景，包含向导被僵尸追赶的动作；它是完整场景，不是独立角色精灵表。主要用于观察步态，不用于替换本项目的服装配色。

用户提供的三个 Bilibili 视频作为补充参考：

| 视频 | 上传者 | 使用范围 |
| --- | --- | --- |
| [泰拉瑞亚NPC图鉴：向导](https://www.bilibili.com/video/BV1km4y1p7p8/) | Katana-健です | 角色及游戏场景参考 |
| [向导](https://www.bilibili.com/video/BV1L4411j72q/) | 此乃一只狗 | 角色动作参考；页面注明原视频来自 CrabBar |
| [泰拉瑞亚NPC介绍合集1-向导](https://www.bilibili.com/video/BV1kP4y1A7hq/) | 劈劈西 | 角色及游戏场景参考 |

视频只查看了页面和部分播放画面，未进行完整逐帧动作采集；因此本项目不声称精确复现这些视频的帧时序。

## 工具与生成说明

- 使用 Codex 的 `hatch-pet` 工作流制作动画资源。
- 图像通过 `imagegen` CLI 和 `gpt-image-2` 辅助生成。
- 后期使用 Pillow 进行确定性的裁切、最近邻缩放、透明背景处理、拼接和预览导出。
- 仓库保留最终资源、生成提示和质量记录；不附带工具安装目录、账户配置、服务商配置或 API 日志。

本项目是非官方同人作品，与 Terraria、Re-Logic、Wiki 维护团队、视频作者和 OpenAI 无官方隶属或背书关系。来源记录不替代许可，详见 [LICENSE.md](LICENSE.md)。
