# 长明局

三集古装短剧的剧本、分镜与制作约束。项目按集协作，每集的改动独立提交和审阅。

## 目录

- `episodes/01/`：第一集《夜验》的分镜、成片对应文本与古代美术约束。
- `episodes/02/`：第二集《分签》，由 qiaosikao 在自己的 PR 中提交。
- `episodes/03/`：第三集《余局》，由 zhangminghan 在自己的 PR 中提交。

目前仓库只准备第一集。第二、三集的本地制作资料还没有提交到本分支。

## 第一集文件

| 文件 | 用途 |
| --- | --- |
| `episodes/01/platform-storyboards.md` | 平台导出的第一集分镜 |
| `episodes/01/aicanvas-storyboards.md` | AICanvas 分镜稿 |
| `episodes/01/period-storyboards.md` | 古代仓廒与人物服制修订分镜 |
| `episodes/01/art-direction.json` | 第一集人物、场景、道具的美术约束 |
| `episodes/01/scene-01-period-revision.md` | 首镜古代质感修订记录 |
| `episodes/01/first-cut-script.txt` | 已制作版本对应的用户原始文本 |

平台导入分镜前，须先从目标项目导出当前模板，逐场核对标题，并查看导入预览。仓廒账册上的准确文字、编号和签名由后期合成；便携灯仅提供移动、调光与定向补光，不承担核验判断。

生成的角色图、场景图和视频仍在 AICanvas 云端；本仓库没有把云端媒体当作本地交付物。API Key、任务状态和接口响应不进入 Git。
